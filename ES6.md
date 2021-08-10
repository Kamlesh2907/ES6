<h1 align = "center">ES6 </h1>
    
**ES6** stands for ECMAScript 6. ECMAScript was created to standardize JavaScript, and ES6 is the 6th version of ECMAScript, it was published in 2015, and is also known as ECMAScript 2015. ECMAScript 2015 was the second major revision to JavaScript.

1. ## Introduction

    *  **JavaScript** is a lightweight and interpreted scripting language. It is known for the development of web pages. It is used for both Client-side and server side developments.

1. ## Data Types In JavaScript

    * There are six basic data types in JavaScript which is also known as **Primitive** data types.

        1. **Strings**
            * String is the series of characters. String in javaScript is same as in other programing language, except that in JavaScript once created Strings cannot be modified.

        1. **Numbers**
            * JavaScript has only one type of numbers. Number can be Written with deimal or without decimal.
        1. **Booleans**
            * A Boolean is a binary logic variable in javascript. It will return either True or False depending on the given condition.
        1. **Undefined**
            * A variable without a value has the value undefined means when we declare a variable and did not intialized it then it has the value undefined and the data type is also undefined.
        1. **Null**
            * A Null Variable means that we are pointing to something that doesn't exists or which is invalid. 
        1. **Object** 
            * It is the most important data-type and forms the building blocks for modern JavaScript.

1. ## Code Samples 

    ```javascript
        var a = "Str";
        var b = "ing";
        var c = a+b;
        console.log(c); // String
    ```

    ```javascript
        var a = 5;
        var b = 6;
        var c = a*b;
        console.log(c); // 30
    ```

    ```javascript
        var a,b;
        a = 5;
        b = sqr(a);
        function sqr(x){
        return a*a;
        }
        console.log(b);//25
    ```
    ```javascript
        var a = 6
        if(a%2 ==0){
        console.log("Even");//Even
        }
        else{
        console.log("Odd");//Odd
        }
    ```
    ```javascript
        let arr = [2,4,5,3,6];
        for(let i = 0;i<arr.length; i++){
            if(arr[i]%2 == 0){
                console.log("Even");//Even
            }
        }
     ```      
1. ## Refrence Link
    * [https://www.geeksforgeeks.org/variables-datatypes-javascript/](https://www.geeksforgeeks.org/variables-datatypes-javascript/)

    * [https://www.w3schools.com/js/js_datatypes.asp](https://www.w3schools.com/js/js_datatypes.asp)
    