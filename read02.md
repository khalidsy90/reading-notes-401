# What’s the difference between PUT and PATCH?

| PUT                                                                                                                                                                                        | PATCH                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| a method of modifying resource where the client sends data that updates the entire resource .                                                                                              | a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.                                                           |
| In a PUT request, the enclosed entity is considered to be a modified version of the resource stored on the origin server, and the client is requesting that the stored version be replaced | With PATCH, however, the enclosed entity contains a set of instructions describing how a resource currently residing on the origin server should be modified to produce a new version. |
| HTTP PUT is said to be idempotent, So if you send retry a request multiple times, that should be equivalent to a single request modification                                               | HTTP PATCH is basically said to be non-idempotent. So if you retry the request N times, you will end up having N resources with N different URIs created on the server.                |
| It has High Bandwidth                                                                                                                                                                      | Since Only data that need to be modified if send in the request body as a payload , It has Low Bandwidth                                                                               |

---

# Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

1. **Nock**
   Nock is an HTTPS library designed to replicate and mock servers and expectations in Node.js. Functionally, Nock does this by overriding both the http.request and http.ClientRequest functions, intercepting requests and responding with a specific mocked response through the use of Interceptors.

2. **MockServer**

   MockServer (and its counterpart service MockServer Proxy) is a multifaceted tool that comes in a variety of builds. It’s available as a Netty web server, a Docker container, a Maven plugin, an npm plugin, and a Grunt plugin. There’s a ton of great options that can be leveraged for a variety of environments. This already makes it a pretty compelling tool given that you can plug it into just about anything you’re running, but its wide range of functionality is the core compelling argument.

3. **Beeceptor**
   Beeceptor is a great tool largely because it requires absolutely no code in order to utilize it. Beeceptor is a free online tool for mocking a REST API interaction using any HTTP request. You can customize your responses to simulate pretty much any response or failure situation. Beeceptor also offers some great functionality to simulate latency on downstream APIs – you can both simulate transmit latency and timeouts, which is a great use case for many APIs and often missed during testing.

---

# Compare and contrast SOAP and ReST

The difference is:

- SOAP is a XML-based message protocol, while REST is an architectural style
- SOAP uses WSDL for communication between consumer and provider, whereas REST just uses XML or JSON to send and receive data
- SOAP invokes services by calling RPC method, REST just simply calls services via URL path
- SOAP doesn't return human readable result, whilst REST result is readable with is just plain XML or JSON
- SOAP is not just over HTTP, it also uses other protocols such as SMTP, FTP, etc, REST is over only HTTP

---

# Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

**apiDocjs**: Inline Documentation for RESTful web APIs. It creates a documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page.

**Swagger**: Test and Document Your APIs With Ease. It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation.

---

# Document the following Vocabulary Terms

**web server** : is software and hardware that uses HTTP (Hypertext Transfer Protocol) and other protocols to respond to client requests made over the World Wide Web. The main job of a web server is to display website content through storing, processing and delivering webpages to users. Besides HTTP, web servers also support SMTP (Simple Mail Transfer Protocol) and FTP (File Transfer Protocol), used for email, file transfer and storage.

**Express**:Express is a minimal and flexible Node.js web application framework that provides a robust set of features to develop web and mobile applications. It facilitates the rapid development of Node based Web applications.

**Routing**:Routing or router in web development is a mechanism where HTTP requests are routed to the code that handles them. To put simply, in the Router you determine what should happen when a user visits a certain page.

**WRRC** : Web Request Response Cycle.

---

- **Which 3 things had you heard about previously and now have better clarity on?**

  - middleware
  - event loop
  - testing

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

- authentication
- CI / CD
- Jest
  **What are you most excited about trying to implement or see how it works?**
- data structure
