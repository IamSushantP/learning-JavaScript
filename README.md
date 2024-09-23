# learning-JavaScript
   Repo of Javascript learning with Notes
   JavaScript is a dynamically typed language

   # Variables in Javascript  -->   
      var x = 5; // declare and assign a value to a variable  (20/08/2024)
      JavaScript variables are containers for storing data values. for eg (var k = 9;)
      var, let, const are used to declare variables in JavaScript.
      
      var -->
        var is function scoped, let and const are block scoped.
        var can be redeclared, let and const cannot be redeclared.
        var can be reinitialized, let and const cannot be reinitialized.
        eg.
            var myVar = 1; (console.log(myVar)  ==> 1)
            myvar = 2; (console.log(myVar)  ==> 2)
            var myV  ar = 3; (console.log(myVar)  ==> 3)

      let ->
         let is block scoped, var is function scoped.
         let cannot be redeclared, var can be redeclared.
         let cannot be reinitialized, var can be reinitialized.
         eg.
         let myVar = 1; (console.log(myVar)  ==> 1)
         myvar = 2; (console.log(myVar)  ==> 2)
         let myVar = 3; (console.log(myVar)  ==> 3)

      const -->
         const is block scoped, var is function scoped.
         const cannot be redeclared, var can be redeclared.
         const cannot be reinitialized, var can be reinitialized.
         eg.
         const myVar = 1; (console.log(myVar)  ==> 1)
         myvar = 2; (console.log(myVar)  ==> 1)



   # Datatypes in Javascript
      Primitive Data Types: (23/08/2023) //call by value
         Number: Represents numeric data, including integers and floating-point numbers.
         String: Represents textual data, enclosed within single or double quotes.
         Boolean: Represents a logical value, either true or false.
         Undefined: Represents a variable that has been declared but not assigned a value.
         Null: Represents the intentional absence of any object value.
         Symbol (introduced in ECMAScript 6): Represents a unique identifier.
         BigInt

         Non-primitive / Reference Type:
               Object: Represents a collection of key-value pairs, where values can be primitives or other objects. Objects can be created using object literals {}, the new Object() syntax, or through constructors.
               Array: Represents a list-like collection of elements, where elements can be of any data type. Arrays can be created using array literals [] or the new Array() syntax.
               Function: Represents executable code and can be treated as objects. Functions can be defined using function declarations, function expressions, arrow functions, etc.


      Special Data Types:
         BigInt (introduced in ECMAScript 2020): Represents arbitrary-precision integers. It allows representing integers beyond the safe integer limit of Number type.
         Symbol (as a primitive type): Represents a unique identifier, primarily used as object property keys to avoid name clashes.


   # Datatype conversion
      In JavaScript, you can convert data types using the following methods:
      1.  **toString()**: Converts a value to a string. 
      //var abc = 10;
      //console.log(abc.toString()); // Output: "10"
      2.  **valueOf()**: Returns the primitive value of an object.
      //var abc = 10;
      //console.log(abc.valueOf()); // Output: 10
      3.  **Number()**: Converts a value to a number.
      //var abc = "10";
      //console.log(Number(abc)); // Output: 10
      4.  **String()**: Converts a value to a string.
      //var abc = 10;
      //console.log(String(abc)); // Output: "10"
      5.  **Boolean()**: Converts a value to a boolean.
      //var abc = 10;
      //console.log(Boolean(abc)); // Output: true
      6.  **parseInt()**: Parses a string argument and returns an integer of the specified
      // var k = "10";
      // console.log(parseInt(k)); // Output: 10
      7.  **parseFloat()**: Parses a string argument and returns a floating point number of
      // var k = "10.5";
      // console.log(parseFloat(k)); // Output: 10.5

   # DataTye Operations
      In JavaScript, you can perform operations on data types using the following methods:
      1.  **Arithmetic Operations**: You can perform arithmetic operations like addition, subtraction, multiplication
      and division on numbers using the following operators: +, -, \*, /, % etc.
      //var a = 10;
      //var b = 5;
      //console.log(a + b); // Output: 15
      //console.log(a - b); // Output: 5
      //console.log(a \* b); // Output: 50
      //console.log(a / b); // Output: 2
      2.  **Comparison Operations**: You can perform comparison operations like equality, inequality, greater than,
      less than, greater than or equal to, less than or equal to using the following operators: ==
      !=, >, <, >=, <= etc.
      //var a = 10;
      //var b = 5;
      //console.log(a == b); // Output: false
      //console.log(a != b); // Output: true


