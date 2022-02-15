# Light a candle
**Version 1.0.0**

Simple p5.js creation made by Jan Dvořák

## Usage
Simple mouse point light.
The goal is to point the mouse at the tip of the candle and light it


```javascript
let locX = mouseX - width / 2;
  let locY = mouseY - height / 2;
  ambientLight(10, 22,10);
  pointLight(255, 255, 255, locX, locY, 50);
  specularMaterial(10);
```
## Script

There is no actual function to this other than the eyes of the character that "move". Just a simple p5.js project.
```javascript
function setup() {
  createCanvas(700, 700, WEBGL );
}
function draw() {
  background(0);
  noStroke();
  let locX = mouseX - width / 2;
  let locY = mouseY - height / 2;
  ambientLight(10, 22,10);
  pointLight(255, 255, 255, locX, locY, 50);
  specularMaterial(10);
  translate(20, 3, 3);
  shininess(30);
  sphere(40);
  translate(60, 3, 4);
  shininess(100);
  sphere(40);
  fill(204);
  

  fill(0, 0, 0);
  ellipse(22, -34, 1402, 802);
  
   fill(255,255 ,255);
  rect(-60, 1610, 3, 203);
  
  
  triangle(12, 18, 18, 360, 81, 300)

  fill(204);
  quad(189, 109, 66, 118, 16, 2, 10, 370);

  fill(204);
  triangle(-142, 48, 22, 12, 10, 500);
  
  fill(255,0 ,42);
  rect(-26, 101, 33, 120);
  
  fill(255,255 ,255);
  rect(3, 161, 33, 23);
  
    fill(255,255 ,255);
  rect(-46, 161, 33, 23);
  
  fill(255);
  ellipse(-22, -34, 202, 202);
  
    fill(255,0 ,42);
  rect(-366, -320, 20, 120);  

   fill(255,0 ,42);
  rect(-346, -210, -50, 20);
  
  fill(255,0 ,42);
  rect(-376, -220, -20, 20);
  
  
    fill(255,0 ,42);
  rect(-306, -320, 20, 130);
  
  fill(255,0 ,42);
  rect(-236, -320, -50, 20);
  
  fill(255,0 ,42);
  rect(-236, -250, -50, 20);
  
  fill(255,0 ,42);
  rect(-250, -320, 20, 130);
  
   fill(255,0 ,42);
  rect(-180, -320, 20, 130);
  
  
   fill(255,0 ,42);
  rect(-110, -320, 20, 130);
  
  fill(255,0 ,42);
  rect(-160, -320, 20, 23);
  
   fill(255,0 ,42);
  rect(-150, -300, 20, 23);
  
     fill(255,0 ,42);
  rect(-140, -280, 20, 23);
  
  fill(255,0 ,42);
  rect(-130, -260, 20, 23);
  
  fill(255,0 ,42);
  rect(-120, -240, 20, 23);
  
}

```
## Contributors
- Jan Dvořák 

## License & Copyright

© Jan Dvořák Programming 