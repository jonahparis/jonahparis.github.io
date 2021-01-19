background(39, 197, 245);
// Fish 
var centerX = 200;
var centerY = 100;
var bodyLength = 100;
var bodyHeight = 74;
var bodyColor = color(153, 79, 161);


var  PurpleFishy= function(centerX,centerY) {
noStroke();
fill(bodyColor);
// body
ellipse(centerX, centerY, bodyLength, bodyHeight);
// tail
var tailWidth = bodyLength/4;
var tailHeight = bodyHeight/2;
triangle(centerX-bodyLength/2, centerY,
         centerX-bodyLength/2-tailWidth, centerY-tailHeight,
         centerX-bodyLength/2-tailWidth, centerY+tailHeight);
// eye
fill(33, 33, 33);
ellipse(centerX+bodyLength/4, centerY, bodyHeight/5, bodyHeight/5);
//fin
fill(255, 0, 0);
ellipse(centerX-10,centerY,30,15);
};


PurpleFishy(100,80);
PurpleFishy(300,80);



 var  TanFishy= function(centerX,centerY) {
noStroke();
fill(217, 178, 87);
// body
ellipse(centerX, centerY, bodyLength, bodyHeight);
// tail
var tailWidth = bodyLength/4;
var tailHeight = bodyHeight/2;
triangle(centerX-bodyLength/2, centerY,
         centerX-bodyLength/2-tailWidth, centerY-tailHeight,
         centerX-bodyLength/2-tailWidth, centerY+tailHeight);
// eye
fill(33, 33, 33);
ellipse(centerX+bodyLength/4, centerY, bodyHeight/5, bodyHeight/5);
//fin
fill(230, 184, 225);
ellipse(centerX-10,centerY,30,15);
};   


TanFishy(124,300);
TanFishy(300,300);


//Pebbles
 var  Pebble= function(centerX,centerY) {
    fill(112, 103, 103);
    ellipse(centerX,centerY,40,20);
};
Pebble(380,390);
Pebble(370,390);
Pebble(330,390);
Pebble(290,390);
Pebble(250,390);
Pebble(210,390);
Pebble(170,390);
Pebble(130,390);
Pebble(90,390);
Pebble(50,390);
Pebble(10,390);
Pebble(350,375);
Pebble(310,375);
Pebble(270,375);
Pebble(230,375);
Pebble(190,375);
Pebble(150,375);
Pebble(110,375);
Pebble(70,375);
Pebble(30,375);
Pebble(-10,375);


//Plants
 var  Plant= function(centerX,centerY) {
    stroke(11, 64, 31);
    fill(65, 110, 22);
     ellipse(centerX,centerY,40,40);
     ellipse(centerX-5,centerY-30,40,40);
     ellipse(centerX+5,centerY-60,40,40);
     ellipse(centerX-5,centerY-90,40,40);
     ellipse(centerX+5,centerY-120,40,40);
     ellipse(centerX-5,centerY-150,40,40);
     ellipse(centerX+5,centerY-180,40,40);
     ellipse(centerX-5,centerY-210,40,40);
     ellipse(centerX+5,centerY-240,40,40);
     ellipse(centerX-5,centerY-270,40,40);
     ellipse(centerX+5,centerY-300,40,40);
     ellipse(centerX-5,centerY-330,40,40);
     ellipse(centerX+5,centerY-360,40,40);
     ellipse(centerX-5,centerY-390,40,40);
};
Plant(370,390);
Plant(30,390);

var CoralFishy= function(centerX,centerY) {
noStroke();
fill(255, 158, 158);
// body
ellipse(centerX, centerY, bodyLength, bodyHeight);
// tail
var tailWidth = bodyLength/4;
var tailHeight = bodyHeight/2;
triangle(centerX-bodyLength/2, centerY,
         centerX-bodyLength/2-tailWidth, centerY-tailHeight,
         centerX-bodyLength/2-tailWidth, centerY+tailHeight);
// eye
fill(33, 33, 33);
ellipse(centerX+bodyLength/4, centerY, bodyHeight/5, bodyHeight/5);
//fin
fill(67, 36, 166);
ellipse(centerX-10,centerY,30,15);
}; 
CoralFishy(200,200);
