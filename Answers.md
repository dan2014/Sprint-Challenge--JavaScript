### 1. Describe the biggest difference between `.forEach` & `.map`.
The biggest difference between the `.forEach` and `.map` is that .forEach can either iterates\ one element at a time, like a for loop, or change the array in place. Map returns an array when it is finished running. 

### 2. What is the difference between a function and a method?
A function is an object that performs a task and can be declared in the global scope. A method is a function that is defined like a property in an object. An object, like an array, has predifined methods that are specific for the object type and can be called with dot notation.

### 3. What is closure?
Closure is scope, similar to local and global scope. A function within a function
can access a variable from the function that contains when the nested function references an variable outside outside of its local scope. When a function is called that contains a nested function is called invokes or returns the nested function, the nested function will attempt to run. If a variable is needed for the nested function to run, it will look in its local scope. If it is not present, it will search for the variable in the closure scope. If it is not present in the closure scope, it will try to find it in the global scope. 

### 4. Describe the four rules of the 'this' keyword.
#### Window/Global object binding
The keyword 'this' in the global scope will reference the propertites and methods defined by Window/Global object.

#### Implicit object binding
The keyword 'this' when using implicit binding will reference the object that called it.

#### new object binding
The keyword 'this' will referece the constructor function's properties and methods.

#### explicit object binding
The keyword 'this' is explicitly defined by using .call() .apply() or .bind().
'this' will reference the object contained in call() .apply() or .bind(). 

### 5. Why do we need `super()` in an extended class?
`super()` allows properties to be added and defined to a child object that has existing properties from a parent object.
