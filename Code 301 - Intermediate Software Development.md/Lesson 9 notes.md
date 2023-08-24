# Functional Programming

1. What is functional programming?

* "A  programming paradigm - a style of building the structure and elements of computer programming - that treats computation as the evaluation of mathetmatical functions and avoids changing-state and mautable data."

2. What is a pure function and how do we know if something is a pure function?

* A pure function returns the same result if given the same arguments, and is also referred to as deterministic. It also does not cause any observable side affects.

3. What are the  benefits of a pure function?

* Predictability, No side effects, Modularity, and concurrency. 

4. What is immutability?

* "Refers to the property of an object or datat structure that cannot be modified after it is created. In other words, once an object is created, it's state cannot be changed."

5. What is Referential transparency?

* "A fundamental concept in functional programming that helps in writing code that is easier to understand, test, and reason. It encourages the use of pure functions and immutable data structures, leading to more reliable and maintainable software systems."

### Node JS for Beginners.

1. What is a module?

* A module is basically a self-contained unit of code that has some kind of functionality attached to it.

2. What does the word 'require' do?

* It's necessary to import and include external libraries, files, or frameworks into whatever current module we are working on.

3. How do we bring another module into the file we are working in?

* We use the 'require' function.
Example: const express = require('express');

4. What do we have to do to make a module available?

* We export the function or library that we are using.