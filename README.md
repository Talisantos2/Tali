# Tali

function setup() {

createCanvas(400, 400);

background("white");

}

function draw() {

stroke("red");

fill("black");

if(mouseIsPressed === false){

rect(mouseY, mouseX,20, 35);

}

}
