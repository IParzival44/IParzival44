
#card {
  border:solid 1px #000;
  width: 300px;
  height: 300px;
  position: absolute;
  -webkit-transition: -webkit-transform 0.4s;
  -moz-transition: -moz-transform 0.4s;
  -o-transition: -o-transform 0.4s;
  transition: transform 0.4;
  -webkit-transform-style: preserve-3d;
  -moz-transform-style: preserve-3d;
  -o-transform-style: preserve-3d;
  transform-style: preserve-3d;
}

figure {
  display: block;
  height: 100%;
  width: 100%;
  line-height: 260px;
  color: white;
  text-align: center;
  font-weight: bold;
  font-size: 45px;
  position: absolute;
  margin: 0;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  -o-backface-visibility: hidden;
  backface-visibility: hidden;
}
.front {background: red;}

.back {
  background: blue;
  -webkit-transform: rotateY( 180deg);
  -moz-transform: rotateY( 180deg);
  -o-transform: rotateY( 180deg);
  transform: rotateY( 180deg);
}
#card:hover {transform:rotateY(180deg);}
