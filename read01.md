# Node Ecosystem, TDD, CI/CD

![](https://cd.foundation/wp-content/uploads/sites/78/2020/09/devops.png)
**Test Driven Development**

Test driven development (TDD) is a software development process that has the developer writing a test, failing it first, then writing code that causes that test to pass. TDD is a preferred method for writing code “because it is the simplest way to achieve both good quality code and good test coverage

**Continuous integration (CI) and continuous delivery (CD)**

Continuous integration is a set of practices that teams of developers use to implement small changes and merge into a shared repository frequently. Continuous Delivery (CD) is the process of deploying software in short cycles by ensuring that software can be deployed at any time.

---

# Array.map()

Sometimes we may need to take an array and apply some procedure to its elements so that you get a new array with modified elements.

Example :

```javascript
let arr = [3, 4, 5, 6];

let modifiedArr = arr.map(function (element) {
  return element * 3;
});

console.log(modifiedArr); // [9, 12, 15, 18]
```

---

# Array.reduce()

similar to other iteration methods like map helps us work through all of the elements of a dataset, performing actions on each one.

Array reduce has two very powerful features:

1. It always returns a single value.
2. You get to choose the data type to be returned.

**syntax: Array.reduce(reducer function(accumulator, currentValue, index, array), initialValue)**

**A reducer function that takes up to four parameters, and An initial value.**

Example :

```javascript
const data = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
];

const flatValues = data.reduce((total, value) => {
  return total.concat(value);
}, []);
```

---

# Superagent()

![Superagent](https://image.slidesharecdn.com/2014-03-13-fluent-140312172643-phpapp01/95/in-pursuit-of-the-holy-grail-building-isomorphic-javascript-apps-13-638.jpg?cb=1394716889)

1. superagent with Promise :

```javascript
agent("GET", "http://google.com").then(function onResult(res) {
  // do stuff
});
```

2. superagent with async / await :

```javascript
async function test() {
  try {
    var response = await request.post("/user/").send({ test: 4 });
  } catch (err) {
    // do something with err...
  }
}
```

---

# Promises

![Promises](https://tutorial.techaltum.com/images/javascript-promise.jpg)
JavaScript works well with imperative and synchronous code but some data like fetching data over the network, could take a while to be available.

**The purpose of using Promises is encapsulate the asynchronicity and allow function handling asynchronous operations to still look synchronous**

- A Promise has four states:

1. fulfilled: Action related to the promise succeeded
2. rejected: Action related to the promise failed
3. pending: Promise is still pending i.e not fulfilled or rejected yet
4. settled: Promise has fulfilled or rejected

Syntax :

```javascript
var promise = new Promise(function (resolve, reject) {
  //do something
});
```

---

**Are all callback functions considered to be Asynchronous?**
![callback functions](https://www.tutsmake.com/wp-content/uploads/2020/05/Callback-Function-JavaScript.jpeg)
Callbacks that you call yourself are regular function calls, which are always synchronous and just regular functions, and they don't know or care whether they're going to be called asynchronously or not but in the same time a callback can be used synchronously or asynchronously.

For a function to be asynchronous it needs to perform an asynchronous operation like :

- timer functions setTimeout, setInterval
- special functions nextTick, setImmediate
- performing I/O (listening to network, querying a database, reading or writing from a resource)
- subscribing to an event
