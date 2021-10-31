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

------------------<!-- markdownlint-capture -->
**Are all callback functions considered to be Asynchronous?**

Callbacks that you call yourself are regular function calls, which are always synchronous and just regular functions, and they don't know or care whether they're going to be called asynchronously or not but in the same time a callback can be used synchronously or asynchronously.

For a function to be asynchronous it needs to perform an asynchronous operation like :

* timer functions setTimeout, setInterval
* special functions nextTick, setImmediate
* performing I/O (listening to network, querying a database, reading or writing from a resource)
* subscribing to an event