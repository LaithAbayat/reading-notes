# Read04

***HTML Links***

HTML offers many of the conventional publishing idioms for rich text and structured documents, but what separates it from most other markup languages is its features for hypertext and interactive documents. This section introduces the link (or hyperlink, or Web link), the basic hypertext construct. A link is a connection from one Web resource to another. Although a simple concept, the link has been one of the primary forces driving the success of the Web.

A link has two ends -- called anchors -- and a direction. The link starts at the "source" anchor and points to the "destination" anchor, which may be any Web resource (e.g., an image, a video clip, a sound bite, a program, an HTML document, an element within an HTML document, etc.).

Although several HTML elements and attributes create links to other resources (e.g., the IMG element, the FORM element, etc.).


***JS Functions***

Generally speaking, a function is a "subprogram" that can be called by code external (or internal in the case of recursion) to the function. Like the program itself, a function is composed of a sequence of statements called the function body. Values can be passed to a function, and the function will return a value.

In JavaScript, functions are first-class objects, because they can have properties and methods just like any other object. What distinguishes them from other objects is that functions can be called. In brief, they are Function objects.

To return a value other than the default, a function must have a return statement that specifies the value to return. A function without a return statement will return a default value. In the case of a constructor called with the new keyword, the default value is the value of its this parameter. For all other functions, the default return value is undefined.

The parameters of a function call are the function's arguments. Arguments are passed to functions by value. If the function changes the value of an argument, this change is not reflected globally or in the calling function. However, object references are values, too, and they are special: if the function changes the referred object's properties, that change is visible outside the function, as shown in the following example:

/* Declare the function 'myFunc' */
function myFunc(theObject) {
  theObject.brand = "Toyota";
}

/*
 * Declare variable 'mycar';
 * create and initialize a new Object;
 * assign reference to it to 'mycar'
 */
var mycar = {
  brand: "Honda",
  model: "Accord",
  year: 1998
};

/* Logs 'Honda' */
console.log(mycar.brand);

/* Pass object reference to the function */
myFunc(mycar);

/*
 * Logs 'Toyota' as the value of the 'brand' property
 * of the object, as changed to by the function.
 */
console.log(mycar.brand);

***Intro to CSS Layout***

CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container, or the main viewport/window.  The page layout techniques we'll be covering in more detail in this module are

-Normal flow
The display property
Flexbox
Grid
Floats
Positioning
Table layout
Multiple-column layout
