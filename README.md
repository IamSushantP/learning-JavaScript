# learning-JavaScript
   Repo of Javascript learning with Notes


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
      Primitive Data Types: (23/08/2023)
         Number: Represents numeric data, including integers and floating-point numbers.
         String: Represents textual data, enclosed within single or double quotes.
         Boolean: Represents a logical value, either true or false.
         Undefined: Represents a variable that has been declared but not assigned a value.
         Null: Represents the intentional absence of any object value.
         Symbol (introduced in ECMAScript 6): Represents a unique identifier.


      Composite Data Types:
         Object: Represents a collection of key-value pairs, where values can be primitives or other objects. Objects can be created using object literals {}, the new Object() syntax, or through constructors.
         Array: Represents a list-like collection of elements, where elements can be of any data type. Arrays can be created using array literals [] or the new Array() syntax.
         Function: Represents executable code and can be treated as objects. Functions can be defined using function declarations, function expressions, arrow functions, etc.


      Special Data Types:
         BigInt (introduced in ECMAScript 2020): Represents arbitrary-precision integers. It allows representing integers beyond the safe integer limit of Number type.
         Symbol (as a primitive type): Represents a unique identifier, primarily used as object property keys to avoid name clashes.


   