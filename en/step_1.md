Functions break your code into particular tasks so it is easier to understand. Especially when you have tasks that need to be done multiple times. They're like tools you can use over and over in different parts of your code.

+ Writing a Function: 
    + start with the function keyword to indicate the creation of a function. Give your function a name (e.g., addNumbers).
    + include brackets `()` after the function name for parameters (inputs) your function needs.
    + use open curly braces `{` to define the block of code that the function will execute.
    + close the curly braces `}` to show the end of the function.

    --- code ---
    ---
    language: js
    filename:
    line_numbers: true
    line_number_start:
    line_highlights:
    ---

        function sayHello() {
           console.log("Hello, World!");
        }
        
    --- /code ---

Here, you've created a simple function named `sayHello`.

+ Using a Function:

    --- code ---
    ---
    language: js
    filename:
    line_numbers: true
    line_number_start:
    line_highlights:
    ---

        sayHello(); // Outputs: Hello, World!
        
    --- /code ---

When you call this function, it will execute the code inside the curly braces and print "Hello, World!" to the console. You can use the function (call it) by writing the syntax shown above.

