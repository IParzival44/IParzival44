- 👋 Hi, I’m @IParzival44@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap");
* {
outline: none;
box-sizing: border-box;
}
body {
background-image: linear-gradient(
0deg,
rgba(247, 247, 247, 1) 23.8%,
rgba(252, 221, 221, 1) 92%
);
font-family: "Open Sans", sans-serif;
margin: 0;
height: 100vh;
display: flex;
align-items: center;
justify-content: center;
flex-direction: column;
}
.music-container {
background-color: #fff;
border-radius: 15px;
box-shadow: 0 20px 20px 0 rgba(252, 169, 169, 0.6);
display: flex;
padding: 20px 30px;
position: relative;
margin: 100px 0;
z-index: 10;
}
.img-container {
position: relative;
width: 110px;
}
.img-container::after {
content: "";
background-color: #fff;
border-radius: 50%;
position: absolute;
bottom: 100%;
left: 50%;
width: 20px;
height: 20px;
transform: translate(-50%, 50%);
box-shadow: 0 0 0px 10px #000;
}
.img-container img {
border-radius: 50%;
object-fit: cover;
height: 110px;
width: inherit;
position: absolute;
bottom: 0;
left: 0;
animation: rotate 3s linear infinite;
animation-play-state: paused;
}
.music-container.play .img-container img {
animation-play-state: running;
}
@keyframes rotate {
from {
transform: rotate(0deg);
}
to {
transform: rotate(360deg);
}
}
.navigation {
display: flex;
align-items: center;
justify-content: center;
z-index: 1;
}
.action-btn {
background-color: #fff;
border: 0;
color: #dfdbdf;
font-size: 20px;
cursor: pointer;
padding: 10px;
margin: 0 20px;
}
.action-btn.action-btn-big {
color: #cdc2d0;
font-size: 30px;
}
.music-info {
background-color: rgba(255, 255, 255, 0.5);
width: calc(100% - 40px);
padding: 10px 10px 10px 150px;
border-radius: 15px 15px 0px 0px;
position: absolute;
top: 0;
left: 20px;
opacity: 0;
transform: translateY(0%);
transition: transform 0.3s ease-in, opacity 0.3s ease-in;
z-index: 0;
}
.music-container.play .music-info {
opacity: 1;
transform: translateY(-100%);
}
.music-info h4 {
margin: 0;
}
.progress-container {
background-color: #fff;
border: 5px;
cursor: pointer;
margin: 10px 0;
height: 4px;
width: 100%;
}
.progress {
background-color: #fe8daa;
border-radius: 5px;
height: 100%;
width: 0%;
transform: width 0.1s linear;
}
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
IParzival44/IParzival44 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
