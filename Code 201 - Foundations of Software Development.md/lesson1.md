# Understanding *how* the internet works; web design/process

1. Compose a short poem descrbing how HTTP sends data between computers.
    * *Ahem* roses are red
             violets are blue
             my device is searching
             for a server, tried and true.
             Grab me the info, and send me the data
             The working stuff, not anything from the beta.

2. Describe how HTML, CSS, and JS files are "parsed" in the browser.
    * According to the article: "The browswer parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
    * So once the HTML file has been read, it's going to look for the CSS reference and then finally any JavaScript files it has found from any script elements within the HTML. In order, it parses as HTML > CSS > JS

3. How can you find images to add to a website?
    * You can either google the type of image you are looking for and save the image using the *save as* function locally to your computer, or you can copy the image's web address and use it for later.

4. How do you create a **String** vs a **Number** in JavaScript?
    * The most basic way to create and identify a string vs a number is as follows: ""
    * A string is a sequence of text that is enclosed with quote marks
    * A number is a number. It doesn't have quotes.

5. What is a *variable* in JavaScript and why are they important?
    * A variable in JS is a "container" that stores values. You declare the variable with let or const, then you give a name to the variable that is related to the purpose of it's function.

# Understanding HTMl 

1. What is an HTML *attribute*?
    * An attribute is information about an element that will not display in the content with the page when it is rendered.

2. Describe the Anatomy of an HTML element.
    * In a *generalized* order: Header > Nav > Main > Sidebar > Footer

3. What is the difference between <article> and <section> element tags?
    * <section> is the generic section of the document. Whereas the <article> represents a complete composition of information within the page or app.

4. What Elements does a "typical" website include?
    * I think this is kind of similar to question 2 so i'll just refer the reader (myself included) to the answer in question 2.

5. How does metadata influence Search Engine Optimization?
    * Metadata influences optimization within search engines by telling them how to read and show websites on the results page.

6. How is the <meta> HTML tag used when specifying metadata?
    * You can use the tag and attach different attributes to it such as <meta charset> to specify the type of characters encoded within the document.

# Misc.

1. What is the first step to designing a website?
    * *project ideation* - Identifying what you want to do and how you are going to accomplish it.

2. What is the most important question to answer when designing a Website?
    * *What **exactly** do I want to accomplish?*

# Semantics

1. Why should you use an h1 element over a span element to display a top level heading?
    * An h1 element is semantic, giving the text meaning. The span element has no semantic value however, so it doesn't get the benefit of importance that the h1 has.

2. What are the benefits of using semantic tags in our HTML?
    * Search engins consider the content within those tags as immportant keywords, boosting the page's search ranking
    * Semantic naming mirrors proper custom element naming.
    * Suggests to the dev the type of data that will be populated.

# What is JavaScript?

1. Describe 2 things that *require* JavaScript in the Browser?
    * The **DOM** (Document Object Model). This is basically whenever there is a popup window appearing on a page, or new content being displayed.
    * The **Geolocation API** retreieves geographical information. This is how Google Maps is able to find your location and show you where you are on a map.

2. How can you add JavaScript to an HTML document?
    * You can creat a separate "app.js" or ".js" file in your code editor and write your code there, then link it to your HTML using a <script> tag, or you can do in-line JS by writing the JS code directly into the HTML.