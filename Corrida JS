function setup() {
  createCanvas(400, 400);
}
let xSpieler1 = 0;
let xSpieler2 = 0;

function draw() {
  background(220);
  textSize(35);
  text("😎", xSpieler1, 100);
  text("🛩️", xSpieler2, 300);
  rect(350, 0, 10, 400);
     function keyReleaser () {
    if (key == "a") {
      xSpieler1 += random(7);
    }
      if (key == "s") {
      xSpieler2 += random(7);
      }
     }
  if (xSpieler1 > 350) {
    text("Spieler 1 hat gewonnen", 20, 200);
    noLoop();
  }
  if (xSpieler2 > 350) {
    text("Spieler 2 hat gewonnen", 20, 200);
    noLoop();
  }
}
