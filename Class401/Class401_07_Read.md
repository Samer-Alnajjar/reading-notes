**Sunday-4/4/2021**

**This is what I learned in class 401_07:**

![Image of JWT](https://res.cloudinary.com/practicaldev/image/fetch/s--Z4uQr_XR--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/lzhrko3j6l8uut86tkz1.png)

![Image of API](https://bytenbit.com/wp-content/uploads/2019/09/Resful-API-cycle.png)

![Image of API clients](https://apaleo.dev/assets/images/oauth/auth_code_flow_first.png)

* I learned the following:

1. Write the following steps in the correct order:

- Register your application to get a client_id and client_secret
- Ask the client if they want to sign in via a third party
- Redirect to a third party authentication endpoint
- Make a request to the third-party API endpoint
- Receive authorization code
- Make a request to the access token endpoint
- Receive access token

2. What can you do with an authorization code?

The authorization code is a temporary code that will give the user the ability to pass the authorization process

3. What can you do with an access token?

Access tokens are used in token-based authentication to allow an application to access an API.

4. What’s a benefit of using OAuth instead of your own basic authentication?

Used to identify the users.

------------------------

### Vocabulary Terms

- Client ID: public identifier for apps
- Client Secret: Secret known only to the OAuth Client and the Authorization Server
- Authentication endpoint: The Authentication API enables you to manage all aspects of user identity when you use Auth0.
- Access Token endpoint: is used by the application in order to get an access token or a refresh token.
- An API endpoint :is a point at which an application program interface (API).
- Authorization code: is a temporary code that the client will exchange for an access token.
- Access Token: An access token is an object encapsulating the security identity of a process or thread.


----------------------
## Preview

1. Which 3 things had you heard about previously and now have better clarity on?

  - basic auth
  - linked list
  - mongodb
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

  - basic auth
  - mongodb
  - data structure


3. What are you most excited about trying to implement or see how it works?

  - basic auth

----------------------
## Preparation Materials

**JSON Web Token** (JWT):  is a JSON object encoded as a long string. We use them to identify users. It’s similar to a passport or driver’s license.

- Generating a JWT

        const jwt = require(‘jsonwebtoken’);

        const token = jwt.sign({ _id: user._id}, ‘privateKey’);

We should Store API leys in environment variables. Use the config package to read application settings stored in environment variables.(as we used to do in 301)

