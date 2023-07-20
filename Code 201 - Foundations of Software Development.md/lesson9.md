# Forms and JS Events; a memoir

## HTML Forms

1. Why are forms so important in web development?
    * Forms are so important because they are how users interact with a website or application in many instances. From the article: "Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way."

2. When designing a form, what are some key things to keep in mind when it comes to the user experience?
    * I would wager things like accessibility, UX, interaction with each part of the page as you are in the wireframing exercise. What do you want the user to fill out? How do you want them to do it in a way that isn't tedious?

3. List 5 form elements and their importance.

    * Input - The text input field is problably the most important form elements. This is where the user is inputting their requested information so that things like search bars and feedback forms can be satisfied.
    * Select (dropdown) - Dropdown menus offer a list of options for the user to choose from. Choices are always good, and variety is the spice of life.
    * Button - People love pressing buttons, figuratively and literally. Buttons can perform a variety of functions that serve to better enhance the UX on your webpage.
    * Checkbox - Checkboxes are essential when users can select one or more options from a list of choices. The best part is you can make multiple choices simultaneously. 
    * Radio Buttons - These are especially useful when there are a limited number of exclusive options like gender choice or ethnic preference. 

    ## Learn JS - EVENTS

1. How would you describe events to a non-technical friend?
    * Events are basically like if you're driving down the road and all of a suddne the train light starts flashing and you have to come to a stop. The lights are letting you know that something (an event) is happening, so that you can brake and let the train pass. 
    
2. When using the addEventListener() method, what 2 arguments do you need to provide?
    * the string "click" in order to indicate that we want to listen to the click event. and then a () function to call when the event happens. 

3. Describe the event object. Why is the target within the event object useful?
    * Becuase the target is passed to the event handler to provide extra features and information.

4. What is the difference between event bubbling and event capturing?
    * The biggest difference is basically which direction the event is going through the DOM. So where is the event listener, what information does it have? And is it going to be able to execute successfully?