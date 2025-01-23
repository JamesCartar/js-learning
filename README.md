1.  **What is JavaScript?**
   
    JavaScript is a browser language that enables interactivity and dynamic behaviours to our web pages.

2. **What is the difference between `var`, `let` and `const` keyword?**

   We can see the difference mostly in three places: **scope**, **hoisting**, and **assignability**. For **scope**, `var` has the _function-scope_, and `let` and `const` have _block-scope_. In **hoisting**, variables declared with `var` get hoisted at the top of their function and global scope and get initialized with the value of `undefined`. But variables declared with `let` and `const` get hoisted to their block scope without any value assigned to it. For **assignability**, variables with `var` and `let` keywords can be reassigned, but for the `const` variable it creates a read-only reference.

3. **What is the difference between `null` and `undefined`?**

   `null` is an assignment value and it can be assigned to a variable as a representation of no value. But `undefined` is a primitive value that represents the absence of value, or a variable that has not been assigned a value.

4. **What is the differenct between `==` and `===`?**

   The `==` equality operator converts the operands if they are not the same type, then applies strict comparison. The `===` strict equality operator only considers value equal if they have the same type and value.

5. **What are the different ways to declare variables in JavaScript?**

   You can declare variable in three ways with `var`, `let` and `const` keywoards.

6. **What are scope in JavaScript?**

   Scope is a set of rules that determine where and how variables and function can be accessed in our code. There are three scope in JavaScript: _global scope_, _function scope_, and _block scope_.

7. **What is ternary operator in JavaScript?**

   A ternary operator is a conditional operator which takes three operands. The first operand is the condition part, the second part which is after the `?` question mark is executed if the condition is evaluated to be true. And the third part which is after the `:` colon is executed if the condition is evaluated to be false. It is frequently used as a shortcut for the `if` statement.

8. **How to implement your own custom event in JavaScript?**

   We can implement our own custom event in JavaScript using `CustomEvent` constructor. `CustomEvent` constructor takes two arguments. The first is the event name and the second argument is the optional object that specified the event option. Then, we can use `dispatchEvent` method to dispatch a custom event on our target element/document. To listend to our custom event on our specified element, we can use `addEventListener` method which accepts the event name and the callback function which is called when the event is dispatched. We can also remove our event with `removeEventListener` method.

9. **What is closure in JavaScript?**

    In JavaScript, a closure is a function that has access to its outer function scope even after the outer function has returned. This means that a function can remember and access variables and arguments of its outer function even after the function has finished.

10. **Does arrow function has their own `this`?**

    No, arrow function does not have their own `this`. Instead, they inherit the `this` of their enclosing lexical scope.

11. **Does `map()` method mutate the original array?**

    No, it does not mutate the original array. It returns a new array with the result of calling a provided function on every element of the array.

12. **Does `forEach() method return a new array?**

    No, it does not return a new array. It simply call the provided function on every element of the array.
