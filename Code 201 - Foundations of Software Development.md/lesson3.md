# HTML Lists, Control Flow with JS, and the CSS Box Model

* These items are important because they help control the structure and flow of the website and how it functions for the end user.

# Ordered and Unordered lists

1. When should you use an *unordered list* in your HTML document?
    * This element should be used when grouping a collection of items that do not have a numerical ordering, and their order inside the list is meaningless.

2. How do you change the *bullet style* of unordered list items?
    * According to MDN, the attributes necessary for changing the appearance of an unordered lists bullets is the **compact** attribute, although the recommended replacement is in CSS as **line-height** which can be assigned a value of 80%.

3. When should you use an *ordered list* vs an *unordered list* in your HTML document?
    * When you want to have a list where the steps or numbered items are important such as a recipe, an ordered list would be more appropriate. Whereas for an unordered list, the order of the bullted items is generally not important and therefore can be used for things like notes or jotting down random points.

4. Describe two ways you can change the numbers on *list items* provided by an *ordered list*
    * You can use the *type* attribute to change the numbers on list items provided by an ordered list.

# Learn CSS

1. Describe the CSS properties of *margin* and *padding* as characters in a story. What is their role in a story titled: "The Box Model"?
    * Once upon a time there was a box. Everyone and everything in the kingdom lived inside of this box. However, there were also other, smaller boxes inside that first box. These boxes all had to live near one another, but after some time had passed, the boxes began to overlap, and war began to wage between them, fighting for space in the space of the biggest box.
    One day, a lord of space and time, *margin*, began to use his powerful staff of moving, and slowly the boxes around him began to shift so that there was space inbetween them. The people roared and cheered as they were finally released from their confinement to the other boxes, free to display their styles without breaking.
    Another powerful lord, *padding*, saw his counterpart *margin* moving the boxes and noticed that the content and people within their boxes were becoming smashed inside their own containers! Lord *margin* chanted ancient arcane spells, and within moments the content within the boxes began to magically shift away from the borders and settled into new space! Thus the **BOX MODEL** was now organized, the lords of margin and padding assuming their thrones as rulers of the CSS.

2. List and describe the **four** parts of an HTML elements box as referred to by the "box model"
    * Content Box
    * Padding Box
    * Border Box
    * Margin Box

# Learn JS

1. What *data types* can you store inside of an *Array*
    * Strings
    * Numbers
    * Objects
    * Other arrays
    * Almost anything can go inside an array

2. Is the *people* array a valid JavaScript array? If so, how can I access the values stored? If not, why?
    * The *people* array is a valid array, it just has a nested array inside of it. So there are 2 instead of 1. In order to access the stored values, we need to put square brackets [] next to our declared array so that we can then specify which index in the array we want to access.

3. List *five* shorthand operators for assignment in JavaScript and describe what they do
    * += Addition operator: Adds value on the right side of the operator
    * -= Subtraction assignment operator: Subtracts the value on the right side of the operator
    * /= Divides the left number by the right
    * %= Remainder: Returns the remainder left over after you've divided the left number equally into the right number
    + **= Exponenet: Raises a base number to the exponent power

4. Read the code below and evalute the last *expression* and explain what the result would be and why.

let a = 10;
let b = 'dog';
let c = false;

//evaluate this
(a + c) + b;

* Okay, so! Because the variable A is a number, B is a string, and C is a boolean, the answer is going to look weird. The answer comes out as '10dog'. JavaScript didn't know what to do with the boolean and said "uh okay so this is zero". Then it saw that we tried to add a number to a string and automatically converted the number into a string, thus giving us '10dog'

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
    * If I had a site that required a username/password in order to access the content, I could use an if/else conditonal statement to prompt the user to create an account, otherwise it returns them back to the main screen or the same prompt.

6. Give an example of when a *loop* is useful in JavaScript.
    * A loop can be useful when a block of code needs to be used or run repeatedly. Such as adding iterations to existing code bases, or a scenario where a set of cirumstances needs to be met before the user can advance in the program or application.