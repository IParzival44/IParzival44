- 👋 Hi, I’m @IParzival44
Menu

How to design HTML Loader using HTML CSS JAVASCRIPT
March 6, 2022 by admin
How to design HTML Loader using HTML CSS JAVASCRIPT
Learner, I’m making a situation for you that Like You are setting on the couch and watching your most awaited web series on Netflix, and accidentally your screen got wrapped with a white spinning circle. That’s the sentiment 😖, Hold on… Hold on I can feel your Feeling, How this much is frustrating. No doubt. This is what we call buffering.


How to design HTML Loader using HTML CSS JAVASCRIPT



Where is used?
It has a huge stretched area where you can sustain this common behaviour, This simply happens because when we work on any particular site at that moment the same site when it unable to fetch a particular weightage of network connectivity then it shows some delays in the preview of buffering.
Like when we try to watch YT videos without network connectivity, some sites show in terms of time out when it failed to fetch the content from the server after requesting and many more.
This is not the only area where we discover, we can also use it knowingly for our use. Like in our project we want to show delays than after the project should be displayed. 



Hey learners!

So, again Welcome to this blog because today we are going to learn and design a loader for ourselves.
We will also see how it is possible to load a page after some time of buffering(time delays).




Before discussing the procedure to make our mini-project. Let have a quick live view of our project, how it’s gonna look like.

See the Pen Html loader 3 by Ankit kumar (@Kumar-Ankit56) on CodePen.

What! No no… You don’t need any master’s degree in front-end development for this project. This blog is only for you. Just keep your hand free for scrolling down to know more in steps.😁.

Prerequisite – You are here and learning this article, So I’m assuming that You have covered all the basic topics of  Front-end development. And still, you are facing problems anywhere the Please visit Codewithrandom for amplifying your knowledge and for a quick recap.


Tool and tech used for this project.
HTML
CSS
JAVASCRIPT(ES6) BASIC
CODEPEN 
VSCODE
BLOG TASKS
 
I will design a loader with an explanation and also show you how can be used for delaying.
HTML SECTION

We will simply draft the formate of HTML in our code editor that we are working on code pen, and will add a div element with the class loader. A class can be anything just for simplification I’m using Loader.
 <!DOCTYPE html>  
 <html>  
 <head>  
 <meta name="viewport" content="width=device-width, initial-scale=1">  
  <title>HTML Loader</title>  
  <meta charset="utf-8">  
  </head>  
 <body>  
 <h2>Keep patience your website is loading</h2>  
 <div class="loader"></div>  
 </body>  
 </html>  
I’m not giving any element to the div tag because we will design the loader just by loader class.

 <div class="loader"></div>  




CSS SECTION

.loader{  
  border: 10px solid #d9d9d9; /* Light grey */  
  border-top: 10px solid #ff3300; /* Blue */  
  border-radius: 50%;  
  margin:auto;  
  width: 120px;  
  height: 120px;  
  animation: spin 2s linear infinite;  
 }  
 h2{  
  text-align: center;  
 }  
 @keyframes spin {  
  0% { transform: rotate(0deg); }  
  100% { transform: rotate(360deg); }  
 }  
Code explanation

In the CSS file, we are targeting div element by loader class in this section I’m giving border so generally border is the property that is used to specify border size and border color.
A border-radius is used to transfer the loader into a circle.
The blue thing that is spinning around and inside of the border is specified by the border-top property, we can also include the following for more spinning of the same color and different colors.
border-left;
border-right;
border-button    
The size of the loader is specified by width and height.
At last, we add a animation that makes the blue thing spin forever with a 2-second animation speed.
See the Pen Html loader 1. by Ankit kumar (@Kumar-Ankit56) on CodePen.



So, this is just a simple loader using HTML and CSS with one border property.


But what if we add this all border property one by one then, Hey Devs why are you concluding Let’s design and have a look.

 <!DOCTYPE html>  
 <html>  
 <head>  
 <meta name="viewport" content="width=device-width, initial-scale=1">  
  <title>HTML Loader</title>  
  <meta charset="utf-8">  
  </head>  
 <body>  
 <h2>Keep patience your website is loading</h2>  
  <div class="container">  
  <div class="loader"></div>  
   <div class="loader1"></div>  
   <div class="loader2"></div>  
   <div class="loader3"></div>  
  </div>  
 </body>  
 </html>  
Same code as above but we are adding 3 more loaders with the different classes to observe all the border property.

 .container{  
  width:100%;  
  height:100vh;  
  display: flex;  
  justify-content:center;  
  align-item:center;  
  margin:10px;  
  padding:10px;  
 }   
 h2{  
  text-align:center;  
 }   
 .loader{  
  border: 10px solid #d9d9d9; /* Light grey */  
  border-top: 10px solid #ff3300;  
  border-radius: 50%;  
  width: 110px;  
  height: 110px;  
  animation: spin 2s linear infinite;  
 }  
 .loader1{  
  border: 10px solid #d9d9d9; /* Light grey */  
  border-top: 10px solid #ff3300; /* Blue */  
  border-bottom: 10px solid #ff1a1a;/* Blue */  
  border-radius: 50%;  
  width: 120px;  
  height: 120px;  
  animation: spin 2s linear infinite;  
  aline-item:center;  
  }  
 .loader2{  
  border: 10px solid #d9d9d9; /* Light grey */  
  border-top: 10px solid #ffb3ff; /* Blue */  
  border-bottom: 10px solid #1a1aff;/* Blue */  
  border-left: 10px solid #ff6666;/* Blue */  
  border-radius: 50%;  
  width: 130px;  
  height: 130px;  
  animation: spin 2s linear infinite;  
 }  
 .loader3{  
  border: 10px solid #d9d9d9; /* Light grey */  
  border-top: 10px solid #ff3300; /* Blue */  
  border-left: 10px solid #ffb3ff;  
  border-right: 10px solid #ff6666;  
  border-bottom: 10px solid #1a1aff;/* Blue */  
  border-radius: 50%;  
  width: 140px;  
  height: 140px;  
  animation: spin 2s linear infinite;  
 }  
 @keyframes spin {  
  0% { transform: rotate(0deg); }  
  100% { transform: rotate(360deg); }  
 }  
 Same as above but we are adding each border property in the subsequent loader with a different color so we can understand its spinning behavior and for beautification.


As you can see the First loader is a simple one with one border property. and the second one we have two border properties as border-top and border-bottom with different colors and continue ahead.
See the Pen Html loader 2 by Ankit kumar (@Kumar-Ankit56) on CodePen.

As we have seen the basics of loader how we can design loader. So, it’s time to learn its use in time Delays and loads a page.


For this, we need logic, and logic is programmed by Javascript. So have a look.
var myVar;  
 function myFunction() {  
  myVar = setTimeout(showPage, 1000);  
 }  
 function showPage() {  
  document.getElementById("loader").style.display = "none";  
  document.getElementById("myDiv").style.display = "block";  
 }  
You must be thinking what is this, So this half complete code. Like if you are planning for some logic events in your projects then your Javascript code must interact with the HTML files this is what we called Dom manipulation.


<!DOCTYPE html>  
 <html lang="en">  
 <head>  
  <title>HTML LOADER</title>  
  <meta charset="utf-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1">  
  <link rel="stylesheet" href="css/style.css">  
 </head>  
 <body onload="myFunction()" style="margin:0;">  
 <div id="loader"></div>  
 <div style=" display:none;" id=" my">  
  <img src="http://ppcdn.500px.org/75319705/1991f76c0c6a91ae1d23eb94ac5c7a9f7e79c480/2048.jpg" width="100%" height="100%"  
 </div>  
 </div>  
 </body>  
 </html>  
  The logic behind Javascript code:


Firstly Loader will rotate for a fixed amount of time that we have placed in the function of my function then after spine content will be loaded.
So firstly loader will spin then the content display will be blocked, and after completion loader display will be blocked and the content will be reviewed.
  
 #loader {  
  position: absolute;  
  left: 50%;  
  top: 50%;  
  width: 120px;  
  height: 120px;  
  border-radius: 50%;  
  border: 16px solid #f2f2f2;  
  margin: -76px 0 0 -76px;  
  border-top: 16px solid #ff3300;  
  animation: spin 2s linear infinite;  
 }  
 @keyframes spin {  
  0% { transform: rotate(0deg); }  
  100% { transform: rotate(360deg); }  
 }  
 #myDiv {  
  display: none;  
  text-align: centre;  
 }  
 HTML, body{  
  height: 100%;  
 }  
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
IParzival44/IParzival44 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
