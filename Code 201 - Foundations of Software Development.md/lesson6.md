# Readings: Problem Domain, Objects, and the DOM

## JS Object basics

1. How would you describe an object to a non-technical friend you grew up with?
    * If I were talking to a non-tech friend, i'd describe it as "A bunch of related information and/or things that work together."

2. What are some advantages to creating object literals?
    * Basically you eliminate all of this little individual tasks and functions that are run line by line and are instead trasnferring a series of structured items in one *package* if you will.

3. How do objects differ from arrays?
    * The easiest example would be that objects represent individual elements or nodes on a web page, so something like a <div> or a <p>. An array differs in that an array is a collection of objects, used to represent multiple elements that share common characteristics. 1 vs the many.

4. Give an example for when you would need to use bracket notation to access an object's property instead of dot notation.
    * *This following quote is direct from the reading*: "However there are some cases where you have to use brackets. For example, if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using *bracket notation*.

5. Evaluate the code below. What does the term *this* refer to and what is the advantage to using *this*?

  const dog = {
    name: 'Spot'
    age: 2,
    color: 'white with black spots',
    humanAge: function (){
        console.log(`${this.name} is ${this.age*7} in human years`);
    }
  }

    * The advantage here of using *this* is that *this* refers to all of the properties of the current object we are examining. Using *this* allows us to reuse the code and call on different objects and only reference the specific properties called on.

## Introduction to the DOM 

1. What is the DOM?
    * According to the related article: "The Document Object Model is the data representation of the objects that comprise the structure and content of a document on the web."

2. Briefly describe the relationship between the DOM and JavaScript.
    * The DOM is an API that is independent of any particular programming language, meaning any or most languages can interface with the DOM. The JavaScript can be used to build webpages by accessing and manipulating the DOM from it's own file. Meaning, you can essentially build an entire HTML document and structure it within the confines of an *app.js* document without actually interfacing with the HTML file.