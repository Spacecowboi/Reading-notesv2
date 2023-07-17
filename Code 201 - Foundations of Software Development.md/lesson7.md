# Object-Oriented Programming, HTML Tables

## Domain Modeling

1. Explain why we need domain modeling
    * A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

### HTML Table Basics

1. Why should tables not be used for page layouts?
    * There are several reasons tables should not be used for page layouts, namely:
    * Layout tables reduce accessibility for visually impaired users.
    * Tables produce *tag soup*. Basically much more complex markup structures than proper layout techniques.
    * Tables are not automatically responsive. Tables are sized according to their content, so extra steps need to be taken to get the table layout styling to work effectively across a variety of devices.

2. List and Describe 3 different semantic HTML elements used in an HTML <table>.
    * <tr> = table row
    * <td> = table data
    * <table> = adding the table to the HTML to begin

### Introducing Constructors

1. What is a constructor and what are some advantages to using it?
    * A constructor function in JS is a special function that creates objects. A major advantage would be that you are able to create many new instances of an object with just a single constructor function isntead of adding numerous individual functions.

2. How does the term *this* differ when used in an object literal versus when used in a constructor?
    * In an object literal, *this* refers to the literal object itself, the current instance of **THAT** particular object. 
    * In a constructor,  *this* then refers to the **NEWLY** created object isntance that is being built by the constructor. 

### Object Prototypes Using a Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.
    * In my previous line of work as a Cannabasic Extraction Technician, a *prototype* that I would have used is setting up for CRC (Color Remediation Cartridge) extraction. The cartridge acts as a *template* that I can then pass all different strains of Cannabis through and assign the same properties and traits without having to change much. The THC properties and values remain the same for each run because they *inherit* the properties of the CRC that I set up initially.