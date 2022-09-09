- 👋 Hi, I’m @IParzival44const carouselContainer = document.querySelector(".carouselContainer");  
 const slides = document.querySelectorAll('.slides');  
 const next = document.querySelector('#next');  
 const prev = document.querySelector('#prev');  
 let counter = 1 ;  
 const size = slides[0].clientWidth;  
 carouselContainer.style.transform = 'translateX(' + (-size * counter ) + 'px';  
 next.addEventListener('click',()=>{  
   if (counter>=slides.length)return;  
   carouselContainer.style.transition = 'transform 0.4s ease-in-out';  
   counter++;  
   carouselContainer.style.transform = 'translateX(' + (-size * counter ) + 'px';  
 });  
 prev.addEventListener('click',()=>{  
   if (counter<=0)return;  
   carouselContainer.style.transition = 'transform 0.4s ease-in-out';  
   counter--;  
   carouselContainer.style.transform = 'translateX(' + (-size * counter ) + 'px';  
 });  
 carouselContainer.addEventListener('transitionend',()=>{  
   console.log(slides[counter]);  
   if(slides[counter].id ==='lastslide'){  
   carouselContainer.style.transition = 'none';  
   counter = slides.length - 2;      
   carouselContainer.style.transform = 'translateX(' + (-size * counter ) + 'px';  
   }  
 });  
 carouselContainer.addEventListener('transitionend',()=>{  
   console.log(slides[counter]);  
   if(slides[counter].id ==='firstslide'){  
   carouselContainer.style.transition = 'none';  
   counter = slides.length - counter;      
   carouselContainer.style.transform = 'translateX(' + (-size * counter ) + 'px';  
   }  
 });  
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
IParzival44 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
