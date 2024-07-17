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


DAY 16
React Routing
React Router is a popular library for implementing routing in React applications. It allows you to create single-page applications (SPAs) with multiple views or pages that can be navigated without causing a full page reload. React Router helps you manage the application's URL and rendering components based on the URL.
To get started with React Router, you need to install the package using npm or yarn:
npm install react-router-dom
Once installed, you can use various components and features provided by React Router to set up routing in your application:
1.	BrowserRouter: This component is used to wrap your entire application. It utilizes the HTML5 History API to handle navigation and updates the URL without triggering a full page reload.
2.	Route: The Route component is used to define a mapping between a specific URL path and a corresponding component that should be rendered when that path is accessed.
3.	Switch: The Switch component is used to render the first Route or Redirect that matches the current location. This is useful when you want to render only one route at a time.
4.	Link: The Link component provides declarative navigation. It's similar to an anchor <a> tag but prevents a full page reload and updates the URL using the React Router mechanism.
Here's a basic example of how to set up routing in a React application using React Router:

DAY-17
React Routing & Javascript String methods

React Routing:
React Routing is a way to handle navigation within a single-page application (SPA) built using the React library. In a traditional multi-page application, clicking on a link would cause the browser to request a new HTML page from the server. However, in a single-page application, the entire page is loaded once, and subsequent navigation is managed within the application itself, without full page reloads. React Router is a popular library for handling routing in React applications.
Key Concepts:
1.	Route: A route represents a specific URL path and is associated with a component that should be rendered when that path is accessed.
2.	BrowserRouter: This is a type of router that uses the HTML5 History API to keep the UI in sync with the URL. It's typically used in web applications.
3.	Route Rendering: When a route's path matches the current URL, the corresponding component is rendered.
4.	Route Parameters: You can define dynamic parts in your route paths using placeholders, which are then accessible as props in the rendered component.
5.	Nested Routes: You can nest routes to create complex page layouts where different components are rendered based on nested URLs.
6.	Link: Instead of using anchor tags (<a>) for navigation, you use the Link component provided by React Router. It prevents full page reloads and updates the URL without refreshing the page.
JavaScript String Methods:
JavaScript provides a variety of methods for working with strings, allowing you to manipulate, transform, and extract information from strings. Here are some commonly used string methods:
1.	charAt(index): Returns the character at the specified index in the string.
2.	concat(str1, str2, ...): Concatenates two or more strings and returns the result.
3.	indexOf(substring, startIndex): Returns the index of the first occurrence of a substring within the string, starting from the specified index.
4.	substring(startIndex, endIndex): Returns a portion of the string between the specified indices.
5.	slice(startIndex, endIndex): Similar to substring, but allows for negative indices to count from the end of the string.
6.	toLowerCase() / toUpperCase(): Converts the string to lowercase or uppercase
7.	trim(): Removes whitespace from the beginning and end of the string.
8.	split(separator): Splits the string into an array of substrings based on the specified separator.
9.	replace(oldValue, newValue): Replaces occurrences of oldValue with newValue in the string.
10.	startsWith(prefix) / endsWith(suffix): Checks if the string starts with the specified prefix or ends with the specified suffix.
11.	length: Returns the number of characters in the string.
These are just a few examples of the many string methods JavaScript provides for various string manipulation tasks. Each method has its own use case and can greatly simplify string-related operations in your code.


DAY-18
React useState hook
The useState hook is a fundamental hook in React that allows functional components to manage state. It provides a way to add state management capabilities to functional components without the need to convert them into class components. Here's how you use the useState hook:
Key points about the useState hook:
1.	The argument passed to useState is the initial value of the state.
2.	The useState hook returns an array with two elements: the current state value and the state update function.
3.	The state update function can be named anything you prefer; setCount in this example is a convention.
4.	When the state is updated using the state update function, React will re-render the component with the new state value.
5.	The state is preserved between renders, making it similar to the state managed by class components.
Using the useState hook, you can manage multiple pieces of state within a functional component, making it a powerful tool for building dynamic UIs in React.
Hookstate and its Features:
As its name suggests, Hookstate is a fast and flexible state management tool based on the React state Hook. It’s a small library packed with features that include both global and local states, as well as partial state updates and asynchronously loaded states.
Our focus for this article is on the @hookstate/core package, but Hookstate has several optional plugins that enable us to extend or customize our state Hooks — and the library’s documentation is well-written and packed with good demos. Below are some noteworthy plugins:
•	@hookstate/persistence enables us to persist our state to the browser’s local storage, which is useful for offline apps or if you’d like a user to retain their state data after reloading the page
•	@hookstate/validation can be very useful for form fields because it enables validation and error/warning messages for a state
•	@hookstate/broadcasted is a very useful tool if you want to enable synchronization of your state across different browser tabs

DAY-19

React Local Storage and Session Storage
Local Storage 
Using localStorage and sessionStorage for storage is an alternative to using cookies and there are some advantages: The data is saved locally only and can’t be read by the server, which eliminates the security issue that cookies present. It allows for much more data to be saved (10mb for most browsers). The syntax is straightforward.


You might want to save more complex types, like for example an object, an array or maybe a number, for that I usually recommend to use JSON.stringify and JSON.parse, which will allow you to save and retrieve said complex types in a string format:

DAY 20

FlexBox and its properties
The flexible box layout module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities. This article gives an outline of the main features of flexbox, which we will be exploring in more detail in the rest of these guides.
When we describe flexbox as being one dimensional we are describing the fact that flexbox deals with layout in one dimension at a time — either as a row or as a column. This can be contrasted with the two-dimensional model of CSS Grid Layout, which controls columns and rows together.

How do I create a flex container using Flexbox?

•	An area of a document laid out using flexbox is called a flex container. To create a flex container, we set the value of the area's container's display property to flex or inline-flex. As soon as we do this the direct children of that container become flex items.

Flexbox Properties
The flex container is the parent element that holds the individual children or flex items. There are several properties we can use to create the flex container we want. Let’s examine the most important flex container properties. As we showed above, display defines a flex container, either inline or block.


DAY 21
Bootstrap carousel and navbar

Bootstrap
A carousel is a slideshow component that displays a series of images or content items. In Bootstrap, you can create a carousel using the Carousel component. Here's how you can set up a basic Bootstrap carousel:

NavBar
Documentation and examples for Bootstrap’s powerful, responsive navigation header, the navbar. Includes support for branding, navigation, and more, including support for our collapse plugin.
How it works
Here’s what you need to know before getting started with the navbar:
•	Navbars require a wrapping .navbar with .navbar-expand{-sm|-md|-lg|-xl|-xxl} for responsive collapsing and color scheme classes.
•	Navbars and their contents are fluid by default. Change the container to limit their horizontal width in different ways.
•	Use our spacing and flex utility classes for controlling spacing and alignment within navbars.
•	Navbars are responsive by default, but you can easily modify them to change that. Responsive behavior depends on our Collapse JavaScript plugin.
•	Ensure accessibility by using a <nav> element or, if using a more generic element such as a <div>, add a role="navigation" to every navbar to explicitly identify it as a landmark region for users of assistive technologies.
•	Indicate the current item by using aria-current="page" for the current page or aria-current="true" for the current item in a set.
Supported content
Navbars come with built-in support for a handful of sub-components. Choose from the following as needed:
•	.navbar-brand for your company, product, or project name.
•	.navbar-nav for a full-height and lightweight navigation (including support for dropdowns).
•	.navbar-toggler for use with our collapse plugin and other navigation toggling behaviors.
•	Flex and spacing utilities for any form controls and actions.
•	.navbar-text for adding vertically centered strings of text.
•	.collapse.navbar-collapse for grouping and hiding navbar contents by a parent breakpoint.
•	Add an optional .navbar-scroll to set a max-height and scroll expanded navbar content.

Day 22
React JS: Building Blocks for Interactive Webpages
•	Imagine building webpages like Legos! ️
•	React JS is a popular JavaScript library for creating dynamic user interfaces.
•	Think buttons, menus, and anything that changes on a webpage.
•	It breaks down complex UIs into reusable components, making development easier.
•	Components are like mini-Legos, each with its own purpose.
•	React keeps track of changes, efficiently updating only what needs refreshing.
•	Dive into React JS to build interactive and engaging web experiences!

Day 23

Node.js: JavaScript Beyond the Browse
•	Imagine JavaScript buzzing around, not just in webpages!
•	Node.js lets you run JavaScript code outside the browser, on the server.
•	Like a beehive, it creates a busy environment for JavaScript to handle requests.
•	This makes it great for building web applications, chat apps, and more.
•	Node.js is known for its speed and efficiency, handling many tasks simultaneously.
•	It's like having a swarm of bees working together!
•	Explore Node.js to unlock the full potential of JavaScript!

Day 24

![image](https://github.com/user-attachments/assets/1165eec3-e702-4806-85a0-0c26118f4b5c)

![image](https://github.com/user-attachments/assets/d5f3c053-80df-4dad-93f8-f594119ad191)


Day 25

![image](https://github.com/user-attachments/assets/39c0d483-3e3a-4332-a275-ad7e2c45b1cc)

![image](https://github.com/user-attachments/assets/fe94eefa-addb-4a04-88ff-ca207c68c354)

Day 26

![image](https://github.com/user-attachments/assets/c3a769db-51df-4eba-b044-3b8cc4ed4392)

![image](https://github.com/user-attachments/assets/e348ec9d-4f17-4aaf-bbf9-2d60b94bc96d)

Day 27

![image](https://github.com/user-attachments/assets/22bb8f12-aebe-457a-b155-4899bbf4f471)

Day 28

![image](https://github.com/user-attachments/assets/c07e0473-303a-4a3f-bc6e-374bdd28a81c)





















