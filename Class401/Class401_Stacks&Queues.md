**Wednesday-7/4/2021**

**This is what I learned in class 401_11:**

![Image of Stack](https://res.cloudinary.com/practicaldev/image/fetch/s--s_Ih2JW7--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/q5a0ym6de9ckp9buhkob.jpg)




- **Stack** is a linear data structure which follows a particular order in which the operations are performed. The order may be LIFO(Last In First Out) or FILO(First In Last Out).

- Mainly the following three basic operations are performed in the stack:

  - Push: Adds an item in the stack. If the stack is full, then it is said to be an Overflow condition.
  - Pop: Removes an item from the stack. The items are popped in the reversed order in which they are pushed. If the stack is empty, then it is said to be an Underflow condition.
  - Peek or Top: Returns top element of stack.
  - isEmpty: Returns true if stack is empty, else false.

----------------------------------
- **Queue** is an abstract data structure, somewhat similar to Stacks. Unlike stacks, a queue is open at both its ends. One end is always used to insert data (enqueue) and the other is used to remove data (dequeue)


![Image of Queue](https://www.tutorialspoint.com/data_structures_algorithms/images/queue_diagram.jpg)

Queue operations may involve initializing or defining the queue, utilizing it, and then completely erasing it from the memory. Here we shall try to understand the basic operations associated with queues −

  - enqueue() − add (store) an item to the queue.

  - dequeue() − remove (access) an item from the queue.

Few more functions are required to make the above-mentioned queue operation efficient. These are −

  - peek() − Gets the element at the front of the queue without removing it.

  - isfull() − Checks if the queue is full.

  - isempty() − Checks if the queue is empty.