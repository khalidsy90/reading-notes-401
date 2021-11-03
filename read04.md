**Name 3 advantages to Test Driven Development**

1. The software design becomes modular
2. The code is easier to maintain
3. Code refactoring goes more smoothly

**In what case would you need to use beforeEach() or afterEach() in a test suite?**
beforeEach() is run before each test in a describe
afterEach() is run after each test in a describe

**What is one downside of Test Driven Development**
Additional Complexity

**What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?**

| ES6 class constructors                                                                                        | ES5 function constructors                                                                                                     |
| ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| As discussed above ES6 class constructors creates objects by adding function to their prototypes (Blueprint). | ES5 function constructors also create objects along with inheritance property.                                                |
| It ensures that this keyword used by the developer is referring to the object being created by the developer. | Any function can be used as a function constructor and it primarily focuses on the creation of reusable object creation code. |
| Its syntax is similar to object creation in other object-oriented programming languages.                      | Its syntax is unique and is not generally found in other object-oriented programming languages.                               |
| This can be said to be a syntax base for constructor functions and instantiate objects using a new operator.  | This also uses a new operator for object creation but focuses on how the objects are being instantiated.                      |

**Why REST?**
designed to take advantage of existing protocols. While REST - or Representational State Transfer - can be used over nearly any protocol, when used for web APIs it typically takes advantage of HTTP. This means that developers have no need to install additional software or libraries when creating a REST API.

---

Vocabulares List
Continuous Integration (CI): stands for Continuous Integration, which is the practice of merging all developers’ working copies to a shared mainline several times a day.

REST: is software architectural style that was created to guide the design and development of the architecture for the World Wide Web.

functional programming: is a way of thinking about software construction by creating pure functions.

object-oriented programming (OOP): is a computer programming model that organizes software design around data, or objects, rather than functions and logic.

class: is a blueprint for creating objects.

super: is the parent class of the derived one.

Test Driven Development (TDD): a software development approach where we write the tests before the code.

Jest: is a JavaScript testing framework maintained by Facebook for tests and such.

Data Model: is an abstract model that organizes data description, data semantics, and consistency constraints of data. The data model emphasizes on what data is needed and how it should be organized instead of what operations will be performed on data.
