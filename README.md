- 👋 Hi, I’m @IParzival44@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
a {
  text-decoration: none;
}
.hero {
  width: 100%;
  height: 100vh;
  background: url(img/bg.png);
  background-size: cover;
}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 30px 100px;
}
.logo {
  max-height: 60px;
}
nav ul li {
  list-style: none;
  display: inline-block;
  padding: 10px 20px;
}
nav ul li a {
  color: #1d1d24;
  position: relative;
  padding: 5px 0;
}
nav ul li a:hover {
  color: #fd4766;
}
nav ul li a:after {
  content: "";
  position: absolute;
  left: 0;
  width: 0;
  height: 3px;
  background: #fd4766;
  transition: 0.3s;
  bottom: 0;
}
nav ul li a:hover:after {
  width: 100%;
}
.btn {
  color: #fff;
  font-size: 16px;
  text-transform: uppercase;
  letter-spacing: 2px;
  padding: 16px 40px;
  border-radius: 500px;
  display: inline-block;
  font-weight: 500;
  transition: all 0.4s ease-in-out;
  background-size: 152% 100%;
  background: #fd4766;
  border: 2px solid #fd4766;
}
.btn:hover {
  background: transparent;
  border-color: #fd4766;
  color: #fd4766;
}
.content {
  position: absolute;
  top: 35%;
  left: 8%;
}
.content .title {
  color: #0a0a0a;
  font-size: 15px;
  text-transform: uppercase;
  letter-spacing: 4px;
  display: inline-block;
  margin-bottom: 20px;
  background: linear-gradient(
    120deg,
    #1c99fe 20.69%,
    #7644ff 50.19%,
    #fd4766 79.69%
  );
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.content h1 {
  color: #1f1f25;
  font-size: 75px;
  font-weight: 900;
  line-height: 90px;
  text-transform: inherit;
  width: 70%;
}
.content h1 span {
  color: #fd4766;
}
.content p {
  width: 55%;
  color: #202020;
  margin-top: 25px;
  margin-bottom: 30px;
}
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
IParzival44/IParzival44 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
