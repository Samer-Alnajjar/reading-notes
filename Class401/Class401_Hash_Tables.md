**Wednesday-5/5/2021**

**This is what I learned in class 401_30:**

![Image of hash table](https://i.imgur.com/2ON8Kt5.jpg)


1. **Hash** A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
2. **Buckets** A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
3. **Collisions**  A collision is what happens when more than one key gets hashed to the same location of the hashtable.
4. We use hash tables for the following:
   - Hold unique values
   - Dictionary
   - Library

5. The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value. This is done through what we call a hash. A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.
6. Hash maps take advantage of an array’s O(1) read access. Instead of adding elements to an array from beginning to end, a hash map uses a “hash function” to place each item at a precise index location, based off it’s key.
7. A hashtable traditionally is created from an array. I always like the size 1024. this is important for index placement. After you have created your array of the appropriate size, do some sort of logic to turn that “key” into a numeric number value. Here is a possible suggestion:

  - Add or multiply all the ASCII values together.
  - Multiply it by a prime number such as 599.
  - Use modulo to get the remainder of the result, when divided by the total size of the array.
  - Insert into the array at that index.

8. Collisions are solved by changing the initial state of the buckets. Instead of starting them all as null we can initialize a LinkedList in each one! Now if two keys resolve to the same index in the array then their key/value pairs can be stored as a node in a linked list. Each index in the array is called a “bucket” because it can store multiple key/value pairs.
9. Hash maps do this to read value:

- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- use the array index to access the short LinkedList representing a bucket
- search through the bucket looking for a node with a key/value pair that matches the key you were given


10. **Bucket Sizes** Hash Maps can have any number of buckets. If a hash map has only a few buckets it will be densely full and have many collisions. If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.

11. Internal Methods:

- **Add()**: When adding a new key/value pair to a hashtable:

- send the key to the GetHash method.
- Once you determine the index of where it should be placed, go to that index.
- Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
- If something does exist, add the new key/value pair to the data structure within that bucket.

- **Find()**: The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

- **Contains()**: The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

- **GetHash()**: The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.