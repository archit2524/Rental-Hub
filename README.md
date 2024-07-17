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

Aim: Create a card with image, title text and description using css.
Code:task1.html

<html lang="en">

<head>

<meta charset="UTF-8">
<link rel="stylesheet" href="./css/task1.css"/>
<title>Document</title>
</head>
<body>
<center>
<div class="card">
<img src="./image/img1.jpg" alt="img">
<h4>Title</h4>
<p>This is description about above thing chfaehhgeur23y23ugqhqh you can see it in image above.</p>
<button>Click</button>
</div>
</center>
</body>
</html>

Code:task1.css
.card{
border:2px solid black; width:250px;
border-radius: 15px;
background-color: rgb(201, 193, 193);} img{
height:150px; width:250px;
border-radius: 15px 15px 0px 0px;} button{
height:50px; width:100px;
background-color: rgb(126, 214, 97); border-radius:15px;}
p,button,h4{ margin:15px;
}

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

Code:task2.html

<html lang="en">
<head>
<meta charset="UTF-8">
<link rel="stylesheet" href="./css/task2.css"/>
<title>Document</title>
</head>
<body>
<center>
<div class="container">
<div class="card">
<img src="./image/img1.jpg" alt="img">
<h4>Title</h4>
 
<p>This is description about above thing chfaehhgeur23y23ugqhqh you can see it in image above.</p>
<button>Click</button>
</div>
<div class="card">
<img src="./image/img1.jpg" alt="img">
<h4>Title</h4>
<p>This is description about above thing chfaehhgeur23y23ugqhqh you can see it in image above.</p>
<button>Click</button>
</div>
</div>
</center>
</body>
</html>

Code:task2.css

.card{
border:2px solid black; float:left; width:400px; height:255px;
background-color:whitesmoke; margin:30px;
text-align: left;
}
img{
height:150px; width:400px;
}
 
button{
background-color: rgb(126, 214, 97); border-radius:15px
}
p,button,h4{ margin:5px;
}
.container{ margin:30px; display:inline-block;
}
center{
background-color:rgb(231, 221, 221);
}

Task 2: create navbar with logo image and items using css float property. Code:task3.html
<html lang="en">

<head>
<meta charset="UTF-8">
<title>Document</title>
<link rel="stylesheet" href=".\css\task3.css"></head>
 
<body>
<div class="nav">
<ul>
<li><img src=".\image\img2tf.png" class="logo"></li>
<li class="l-item">Python</li>
<li class="l-item">SkLearn</li>
<li class="l-item">Pandas</li>
<li class="l-item">Keras</li>
</ul>
</div>
</body>
</html>
Code:task3.css ul{
list-style-type: none;}
li{
float:left;}
img.logo{ height:55px;}
.nav{
height: 55px;
background-color: rgb(0, 200, 255); color:white;
}
.l-item{
margin: 15px; font-size: 20px;}


Task 3: create card with left side image and right side text using css float property.

Code:task4.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial- scale=1.0">
<title>Document</title>
<link rel="stylesheet" href="./css/task4.css"/>
</head>
<body>
<div class="container">
<div id="p1">
<p>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla consequatur doloribus reiciendis labore, odio libero ad, suscipit id quis, quisquam aut quam? Ex hic distinctio nesciunt omnis, fugit tenetur beatae.
</p>
</div>
<div id="i1">
<img src="./image/img1.jpg" alt="img">
</div>
</div>
 
<div class="container">


<div id="i1">
<img src="./image/img1.jpg" alt="img">
</div>
<div id="p1">
<p>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla consequatur doloribus reiciendis labore, odio libero ad, suscipit id quis, quisquam aut quam? Ex hic distinctio nesciunt omnis, fugit tenetur beatae.
</p>
</div>
</div>
</body>
</html> Code:task4.css #p1{
float:left; height: 255px; width:455px;
} #i1{
float:left; height: 255px; width:355px;
margin-left: 5px; margin-right:5px;
}
 
img{
height: 255px; width:355px;
}
.container{ display:block; height: 255px; width:820px; margin:25px;
background-color: whitesmoke;
}

Task 4: create nav-bar and container at left-side and another container on right side using float property.

Code:task5.html:

<html lang="en">
 
<head>
<meta charset="UTF-8">
<link href=".\css\task5.css" rel="stylesheet">
<title>Document</title>
</head>
<body>
<div>
<ul class="nav">
<div class="nav-item"> <li > <img class="logo" src="https://picsum.photos/200" alt="img"></li></div>
<div class="nav-item"> <li>Python</li></div>
<div class="nav-item"><li >JavaScript</li></div>
<div class="nav-item"><li >Java</li></div>
<div class="nav-item"><li >HTML</li></div>
<div class="nav-item"><li >C++</li></div>
</ul>
</div>
<div class="container1">
<ul class="ul2">
<div class="col"> <li>column1</li></div>
<div class="col"> <li>column2</li></div>
<div class="col"> <li>column3</li></div>
<div class="col"> <li>column4</li></div>
<div class="col"> <li>column5</li></div>
<div class="col"> <li>column6</li></div>
<div class="col"> <li>column7</li></div>
<div class="col"> <li>column8</li></div>
<div class="col"> <li>column9</li></div>
</ul>
</div>
<div class="container2">
<div class="p1">
<p>
Lorem ipsum dolor sit amet consectetur, adipisicing elit. Explicabo aut ut quasi! Ullam dolore vitae magnam non nihil nisi autem natus
</p>
</div>
<div class="p1">
<p>
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum voluptas consectetur ullam ex suscipit. Molestiae repudiandae maxime ipsa suscipit, error
</p>
</div>
<div class="p1">
<p>
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum voluptas consectetur ullam ex suscipit. Molestiae repudiandae maxime ipsa suscipit, error
</p>
</div>
<div class="p1">
<p>
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum voluptas consectetur ullam ex suscipit. Molestiae repudiandae maxime ipsa suscipit, error
</p>
</div>
</div>
</body>
</html>
 
Code:task5.css
.nav-item{ float:left; margin:15px; }
.nav{
list-style-type: none; display:block; height:55px; background-color:black; color: white;
padding-left: 2px; margin-left:30%; margin-right:30%; border:2px solid white; border-radius:15px;}
.logo{
height:25px; width:25px;
border-radius: 50%;}
.container1{ height:100%; float:left; display:inline;
background-color: whitesmoke;}
.container2{ margin:20px; height:100%; width:60%; border:2px solid green;
 
float:left; display:inline;}
ul{list-style-type: none;}
.ul2{
list-style-type: none; margin:0px; padding:0px;}
.col{margin:30px;}
.p1{display:inline;} p{margin:25px;}


