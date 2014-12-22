Task10

//This is to put the vessel 

PImage img;

void setup(){
  size(500,500);
img = loadImage("vessel.png");
}
void draw(){
background(0);
image(img, 0, 0, width/5, height/5);
}

======
