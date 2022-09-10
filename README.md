- 👋 Hi, I’m @IParzival44@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');  
 *{  
   margin: 0;  
   padding: 0;  
   box-sizing: border-box;  
   font-family: 'Poppins', sans-serif;  
 }  
 body{  
   display: flex;  
   justify-content: center;  
   align-items: center;  
   height: 100vh;  
 }  
 ul li{  
   width: 200px;  
   height: 35px;  
   display: flex;  
   align-items: center;  
   margin: 1.5em;  
   cursor: pointer;  
   padding: 1em;  
   background:rgb(43, 43, 43);  
   position: relative;  
   color: white;  
   border-radius: 5px;  
 }  
 ul li::before,  
 ul li::after{  
   content: '';  
   position: absolute;  
   z-index: -1;  
   border-radius: 5px;  
   width: 105%;  
   transition: all .4s;  
 }  
 ul li::before{  
   left: 0%;  
   height: 130%;  
   background: linear-gradient(to right, #021B79, #0575E6);  
 }  
 ul li::after{  
   left: -10%;  
   height: 120%;  
   background: #ffffff56;   
   backdrop-filter: blur(10px);  
   box-shadow: 0 0 20px rgba(0, 0, 0, 0.164);  
 }  
 ul li:hover::before{  
   transform: translateX(-2.5%);  
 }  
 ul li:hover::after{  
   transform: translateX(15%);  
 }  
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
IParzival44/IParzival44 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
