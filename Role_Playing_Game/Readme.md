Note:
Variables declared by let are only available inside the 
block where they're defined. Variables declared by var are available throughout the function in which they're declared.
--> If a value it's not going to be re-assign it is best practice to use "const"

Interaction between Javascript and HTML using 
Document Object Model (DOM).
DOM - A tree of objects that represent the HTML

**Access HTML - Use HTML "document" object which represents the entire HTML document.
**Finding elements in HTML - "querySelector()" method.

The "querySelector()" takes a CSS selector as an argument and returns the first element that matches that selector

**Comments

// hello world
/*Hello World*/

**Accessing properties 

.notation -> button.onclick

**Properties 
onclick
innerText - controls the text that appears in an HTML element.

**Manipulation of text
In short, escaping quotes with a backslash is necessary when you want to include quote characters inside a string that's delimited by the same type of quotes.
Example: "He said, \"Hello, World!\"";

**Arrays
*Transition from using arrays for storing strings to using them for storing objects. 

Unlike arrays that are often used for storing similar data types (like strings), arrays can also hold various data types, including objects. Objects differ from arrays primarily in how they store and access data. While arrays use indexes, objects use named properties or keys. These properties or keys are used to access and modify the data within an object. An object is represented by curly braces, and an example of an empty object is shown as `{}`.

*Using Object properties
{
    name: "David",
    "favorite color": "purple"
}



