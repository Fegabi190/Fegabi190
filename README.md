function setup() {

createCanvas(1000, 1000);

background("salmon");

color(random(255), random(255), random(255));

posicaoHorizontal = 200;

posicaoVertical = 200;

}

function draw() {

fill("pink");

circle(posicaoVertical, posicaoHorizontal, 50);

if(mouseX < posicaoHorizontal){

posicaoHorizontal++;

}

if(mouseX > posicaoHorizontal){

posicaoHorizontal--;

}

if(mouseY < posicaoVertical){

posicaoVertical++;

}

if(mouseY > posicaoVertical){

posicaoVertical--;

}

}

