# Review, Research, and Discussion

**Name 3 real world use cases where you’d want to change the request with custom middleware**

- bad request
- Authentication
- Async Actions

**True or false: The route handler is middleware?**

- false

**In what ways can a middleware function end the process and send data to the browser?**

- a middleware needs to end the request-response early, simply by call next()

**At what point in the request lifecycle can you “inject” middleware?**

- after the request before the response

**What can cause express to error with “Request headers sent twice, cannot start a second response”**

- when I have more than one response being sent to the client

---

| Term                    | Meaning                                                                                                                                                                                                                                                   |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Middleware              | functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next. |
| Request Object          | object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers                                                                                                                                        |
| Response Object         | The res object represents the HTTP response that an Express app sends when it gets an HTTP request                                                                                                                                                        |
| Application Middleware  | include database middleware, application server middleware, message-oriented middleware, web middleware and transaction-processing monitors.                                                                                                              |
| routing in middleware?  | Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware.                                                                     |
| Test Driven Development | a development technique where you must first write a test that fails before you write new functional code                                                                                                                                                 |
| Behavioral Testing      | testing of the external behaviour of the program, also known as                                                                                                                                                                                           |

---

**Which 3 things had you heard about previously and now have better clarity on?**

- Routing
- Middlewaree
- unit testing

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

- Middlewares
- Authentication
- TDD

**What are you most excited about trying to implement or see how it works?**
TDD
