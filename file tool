void mainMenu() {
  background(181, 206, 235);
  fill(255);
  rect(width/2 -200, height/2 + 300, 400, 100);
  fill(0);
  textSize(60);
  text("Start!", width/2 -63, height/2 + 365);
}

void gameOver() {
  background(181, 206, 235);
  fill(255);
  textSize(100);
  text("Gameover!", width/2-200, height/2);
}

void mousePressed() {
  if (state == 0) {
    if (mouseX > width/2 - 200 && mouseX < width/2 + 200
      && mouseY > height/2 + 300 && mouseY < height/2 + 400)
      state =1;
  }
}
