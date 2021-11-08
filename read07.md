![](https://developer.atlassian.com/cloud/connect/images/connect-oauth-impersonation-flow.png)

**Write the following steps in the correct order**

1.Register your application to get a client_id and client_secret
2.Ask the client if they want to sign in via a third party
3.Make a request to a third-party API endpoint
4.Redirect to a third party authentication endpoint
5.Make a request to the access token endpoint
6.Receive access token
7.Receive authorization code

**What can you do with an authorization code?**

An authorization code allows you to send information, such as a request for an access token, to a secure resource.

**What can you do with an access token?**

Access tokens are used to make API requests on behalf of a user

**What’s a benefit of using OAuth instead of your own basic authentication?**

OAuth contains authorization requests, access tokens and refresh tokens and widely accepted as the standard for modern web applications. It is well documented and easy to implement.

**Document the following Vocabulary Terms**

**Client ID:**

unique identifier , is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string.

**Client Secret:**

Used to authenticate client and is only known by the server and client
Authentication Endpoint:
used to request access tokens or authorization

**Access Token Endpoint:**

used to get an access token or refresh token and its A token endpoint is an HTTP endpoint that micropub clients can use to obtain an access token given an authorization code.

**API Endpoint:**

the connection used to communicate with an API meaning is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service.

**Authorization Code:**

allows you to send information, such as a request for an access token, to a secure resource ,and is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.

**Access Token:**

used for token-based authentication , are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.
Preview

**Which 3 things had you heard about previously and now have better clarity on?**

bearer authentication, jwt, access tokens

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

sessions, extra layers of encryption for JWTs, securing JWTs

**What are you most excited about trying to implement or see how it works?**
sessions and extra layers of encryption with JWTs
