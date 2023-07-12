# HTML Hyperlinks, CSS Layouts, continued JS Learning.

* These topics are detrimental to continuing my understanding of how HTML, CSS, and JS work as one cohesive unit.

## Learn HTML (hyperlinks)

1. To create a basic link, we wrap text or other content inside what element?
    * A basic link is created by wrapping the text or other content inside an <a> element and using the *href* attribute, also known as a **Hypertext Reference** or, **target** that contains the web address.

2. The *href* attribute contains what information?
    * It contains the web address or the *URL*.

3. What are some ways we can ensure links on our pages are accessible to all readers?
    * Screen reader users like jumping around from link to link on the page, and reading links out of context.
    * Search engines use link text to index target files, so it is a good idea to include keywords in your link text to effectively describe what is being linked to.

## CSS Layout: Normal Flow CSS Layout: Positioning.

1. What is meant by "normal flow"?
    * "normal flow" means the way that webpage elements lay themselves out if you haven't changed their layout.

2. What are a few differences between *block-level* and *inline* elements?
    * To keep things concise; a block-level elemetn's content fills the available inline space of the parent element container. An inline-block element is only the size of their content, not the parent container.

3. **Static** positioning is the default for every HTML element.

4. Name a few advantages to using absolute postioning on an element.
    * Precise placement 
    * Ability to overlap elements - you can stack elements in a specific way and control their visibility
    * Isolation - Having the ability to control individual elements 

5. What is a key difference between fixed positioning and absolute positioning?
    * "Whereas absolute positioning fixes an element in place relative to its nearest positioned ancestor, *fixed positioning* usually fixes an element in place relative to the visible portion of the viewport."

## Learn JS

1. Describe the difference between a function declaration and a function invocation.
    * Declaration of a function is a way to name/define a function in JS. Invocation is the action which *executes* the function.

        Ex: function sayHello(name){
            console.log("what up, " + name + "!");
        }

        invocation: sayHello("Steve");

2. What is the difference between a parameter and an argument?
    * A parameter is the set of values that are included inside the function parenthesis. An argument is the set of values that is compared against the set parameters to evaluate if the condition is true or false in order to properly execute the function.

## Misc

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
    * Engaged Collaboration - I feel as though working with others to expand your ability to be creative and innovative is paramount to success not just in the field of software development, but any vocation or trade. 

    * Learning from fellow students - I think one of the best sources of teaching is the experience of others. We are all full of our own individual experiences that are not only useful for us to refelct on personally in order to glean wisdom and knowledge from, but also useful for those around us so they don't make the same mistakes that we had to make.