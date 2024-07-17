Internship_Project(D22IT182)

Day1:
Introduction to web development:
Web development is the process of creating and building websites and web applications that are accessible via the internet. It encompasses a broad range of skills and technologies, combining both front-end and back-end development
Front-end Development:
Also known as client-side development, front-end development focuses on the visual and interactive aspects of a website. Front-end developers use following technologies such as HTML , CSS , PHP , Bootstrap, React , Django ,Tailwind CSS , Flask etc.. to create the structure, layout, and functionality that users interact with directly in their web browsers.
Back-end Development:
Back-end development, also referred to as server-side development, deals with the behind-the-scenes logic and operations of a website. Back-end developers work with server-side languages like PHP, Python, Ruby, or JavaScript (Node.js) to manage databases, handle user authentication, and process data, ensuring that the web application functions smoothly.

Day 2:
Basic introduction of css:

CSS, which stands for Cascading Style Sheets, is a fundamental technology used in web development to control the presentation and layout of HTML documents. It is a stylesheet language that describes how HTML elements should be displayed on a web page or in other media.

We can implement css in 3 ways:

1. inline: within the opening tags of the element. If we use inline css and also use external or internal than first priority is given to inline css.
2. internal: style tag within the head tag. If we use internal and external css than first priority is given to internal css.
3. external: make an external css file and link it.

Day 3:
Task1:
 Create a card with image, title text and description using css.

Day 4:
Background-image and it’s properties:

The background-image property sets one or more background images for an element.

By default, a background-image is placed at the top-left corner of an element, and repeated both vertically and horizontally.

background-size property:

The background-size property specifies the size of the background images.

Values:

cover: Resize the background image to cover the entire container, even if it has to stretch the image or cut a little bit off one of the edges.

contain: Resize the background image to make sure the image is fully visible.

auto: Default value. The background image is displayed in its original size.

length: Sets the width and height of the background image.

background-repeat property:

The background-repeat property sets if/how a background image will be repeated.

Values:

repeat: The background image is repeated both vertically and horizontally.

repeat-x: The background image is repeated only horizontally. repeat-y: The background image is repeated only vertically. no-repeat: The background-image is not repeated.
background-position property:
 
The background-position property sets the starting position of a background image.

Values: left top, left center, left bottom, right top, right center, center top, center center, center bottom

Float property:

The float property specifies whether an element should float to the left, right, or not at all.

Values: none, left, right Clear property:
The clear property controls the flow next to floated elements.

The clear property specifies what should happen with the element that is next to a floating element.

Values: left, right, both. Task1:
Aim: Create two rectangular card with image, title text and description using css float property.

Task 3: create card with left side image and right side text using css float property.

Task 4: create nav-bar and container at left-side and another container on right side using float property.

Day 5:
Position property:

The position property specifies the type of positioning method used for an element (static, relative, absolute, fixed).
After position property we can apply top,left,bottom,right values negative or positive both.

Overflow property:

The overflow property specifies what should happen if content overflows an element's box.

Values:

hidden: The overflow is clipped, and the rest of the content will be invisible.

scroll: The overflow is clipped, but a scroll-bar is added to see the rest of the content.

Hover:

The :hover selector is used to select elements when you mouse over them.

If we want to apply change on another element when hover on element than we can perform it by .classname:hover > .classname {}
Task 1: create 3 cards with image and text on image using position property.
Task 2: create 3 cards with center image and text using position property. 

DAY-6
Flex property in css:

CSS Flexbox is a powerful layout model that allows you to create flexible and responsive designs for web pages. It provides an efficient way to distribute space, alignment, and positioning of elements within a container. The flex layout consists of a parent container (flex container) and its child elements (flex items). The flex container can be displayed horizontally or vertically, and it controls the layout of its flex items.

To use flexbox, you need to set the display property of the container to flex, and then use various flex-related properties to control the layout of the child elements.

flex-direction:

The flex-direction property specifies the direction of the flexible items. Values:row,column.
justify-content:

The justify-content property aligns the flexible container's items when the items do not use all available space on the main-axis (horizontally).

Values:

center: Items are positioned in the center of the container. space-between: Items will have space between them.
space-around: Items will have space before, between, and after them. space-evenly: Items will have equal space around them.
align-content:

The align-content property specifies how flex lines are distributed along the cross axis in a flexbox container.

CSS Gradients:

 CSS Linear Gradients:
 
To create a linear gradient you must define at least two color stops. Color stops are the colors you want to render smooth transitions among. You can also set a starting point and a direction (or an angle) along with the gradient effect.

Syntax:

background-image: linear-gradient(direction, color-stop1, color-stop2,
...);

CSS Radial Gradients:

A radial gradient is defined by its center.

To create a radial gradient you must also define at least two color stops.

Syntax

background-image: radial-gradient(shape size at position, start-color

Task1:create a navbar using flex property that have logo and items and when hover on item sub-items dropdown display .

DAY7
Media-query: for making responsive website Syntax:
@media screen and (min-width/max-width: value px) { selector {

css }
}

min-width: for screen minimum width and above it.

max-width: for screen maximum width and below it. 

DAY8
 
Bootstrap is a html,css framework using which we can easily create responsive UI using classes which are already defined.
We can download bootstrap folder or we can link the bootstrap using
<link> tag.
Background color:
Similar to the contextual text color classes, easily set the background of an element to any contextual class. Anchor components will darken on hover, just like the text classes. Background utilities do not set color, so in some cases you’ll want to use .text-* utilities.

 
 
DAY9

Bootstrap: 
Exploring bootstrap website: https://getbootstrap.com/docs/4.6/getting- started/introduction/

Task :create carousel with left side image and right side text using bootstrap. 


DAY10
JavaScript

JavaScript is a widely used programming language primarily known for its role in web development. It enables interactive and dynamic behavior on websites, making them more engaging and user-friendly. JavaScript allows you to create, manipulate, and modify website content in real-time without requiring a page refresh.
Key features of JavaScript include:
Client-Side Scripting: JavaScript runs in web browsers, allowing it to manipulate the Document Object Model (DOM) of a webpage. This means you can change elements on a page, handle user interactions (such as clicks and form submissions), and update content without needing to communicate with a server.
Event-Driven Programming: JavaScript is event-driven, meaning it responds to events like user actions (clicks, key presses, etc.) or changes in the webpage state. You can define functions to execute when specific events occur.
Dynamic Content: JavaScript allows you to create dynamic and interactive content, such as animations, form validations, real-time updates, and more. This enhances user experience by making websites more responsive and engaging.
Libraries and Frameworks: There are numerous libraries and frameworks built on top of JavaScript, such as jQuery, React, Angular, and Vue.js, which simplify complex tasks and provide reusable components for building web applications.
Asynchronous Programming: JavaScript supports asynchronous programming, allowing you to execute tasks without blocking the main thread. This is crucial for handling tasks like fetching data from servers or performing time-consuming operations without freezing the user interface.


Applications:
Web Development: JavaScript is primarily known for its role in web development. It is used to create interactive and dynamic websites, handle user interactions, update content in real-time, and enhance the user experience.
 
Front-End Frameworks and Libraries: JavaScript frameworks and libraries like React, Angular, and Vue.js are used to build complex user interfaces and single-page applications (SPAs). These tools provide efficient ways to manage state, handle routing, and create reusable UI components.
Mobile App Development: Frameworks like React Native and frameworks powered by technologies like Apache Cordova allow developers to build mobile apps using JavaScript. This enables code reuse between web and mobile platforms.
Game Development: JavaScript can be used to create browser-based games and interactive multimedia content. HTML5 game engines like Phaser and Three.js utilize JavaScript to create engaging gaming experiences.


Datatypes in JS:
Primitive Data Types:
Number: Represents both integer and floating-point numbers.
String: Represents a sequence of characters, such as text.
Boolean: Represents a logical value, either true or false.
Null: Represents the intentional absence of any value.
Undefined: Represents a variable that has been declared but hasn't been assigned a value.
Reference Data Types:
Object: Represents a collection of key-value pairs, where values can be of any data type, including other objects. Objects can be created using object literals or through constructors.
Array: A special type of object that holds an ordered list of values, typically of the same type. Arrays are used for storing collections of data.
RegExp (Regular Expression): Represents a pattern used for matching strings.


DAY11
 

The JavaScript if-else statement is used to execute the code whether condition is true or false. There are three forms of if statement in JavaScript.

1.	If Statement
2.	If else statement
3.	if else if statement JavaScript If statement
It evaluates the content only if expression is true. The signature of JavaScript
if statement is given below.

if(expression){
//content to be evaluated
}

JavaScript If...else Statement

It evaluates the content whether condition is true of false. The syntax of JavaScript if-else statement is given below.

if(expression){
//content to be evaluated if condition is true
}
else{
//content to be evaluated if condition is false
}

JavaScript If...else if statement

It evaluates the content only if expression is true from several expressions. The signature of JavaScript if else if statement is given below.

if(expression1){
//content to be evaluated if expression1 is true
}
else if(expression2){
 
//content to be evaluated if expression2 is true
}
else if(expression3){
//content to be evaluated if expression3 is true
 
}
else{

}
 


//content to be evaluated if no expression is true
 
JavaScript Loops
The JavaScript loops are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

There are four types of loops in JavaScript.

1.	for loop
2.	while loop
3.	do-while loop
4.	for-in loop

1)	JavaScript For loop
The JavaScript for loop iterates the elements for the fixed number of times. It should be used if number of iteration is known. The syntax of for loop is given below.

for (initialization; condition; increment)
{
code to be executed
}



2)	JavaScript while loop
The JavaScript while loop iterates the elements for the infinite number of times. It should be used if number of iteration is not known. The syntax of while loop is given below.
 
while (condition)
{
code to be executed
}

3)	JavaScript do while loop
The JavaScript do while loop iterates the elements for the infinite number of times like while loop. But, code is executed at least once whether condition is true or false. The syntax of do while loop is given below.

do{
code to be executed
}while (condition);

Day 12
JavaScript Array
Array is an object that represents a collection of similar type of elements. But, in JavaScript array we can store different types of elements.

DAY13
JavaScript Objects

JavaScript Objects is used to store key-value pair. Syntax:
object={
key : value, key : value, key : value,
…
}
Day 14:

![image](https://github.com/user-attachments/assets/6305e407-cd04-4b7b-aadd-1b09593ef8ba)

task1 print reverse of the word 
task2 print and count vowels present in string 
task3 convert characters at even places in string into 

DAY15
task-1 write program that print both string //are equal after combining each element of //array.
task2 print the string in reverse order word//wise.
task3 print string having maximum words from//array of strings.












