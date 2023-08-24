# Understanding the JavaScript Call Stack

1. What is a 'call'?

* "A data structure that uses the Last in, First Out principle to temporarily store and manage function invocation"

2. How many 'calls' can happen at once?

* "Since the call stack is single, function(s) execution, is done one at a time, top to bottom. This also means the call stack is synchronous."

3. What does LIFO mean?

* "It means that the last function gets pushed into the stack is the first to pop out, when the function returns."

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

   Call Stack:
   -------------
   |           |
   |           |
   |           |
   |           |
   |___________|
   
   Functions:
   1. main()
   2. functionA()
   3. functionB()
   4. functionC()

(Drawn with ChatGPT) 

5. What causes a Stack Overflow?

* "A stack overflow occurs when there is a recursive function (a fucntion that calls itself) without an exit point. 

### JavaScript error messages

1. What is a reference error?

* A reference error occurs when you try to access a function or variable that isn't scoped or hasn't been declared yet.

2. What is a syntax error?

* A syntax error happens when the JS code breaks the syntax rules. Usually a grammar mistake or code structure problem.

3. What is a range error?

* A range error happens whe n a numeric value is not within the necessary and accepted range declared within the function.

4. What is a type error?

* A type error occurs when an operation or function is executed on a value of an inappropriate type. Like trying to call a non-function as a function.

5. What is a breakpoint?

* A breakpoint is a debugging feature that lets you pause the execution of your code at a specific poiint. So like a 'break';.

6. What does the word debugger do in your code?

* Debugger lets you trigger a different kind of breakpoint that then walks you through the function at the point of execution. There you can do things like inspect your variables, walk through the code line-by-line and analyze the program's state.