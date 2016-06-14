# angryBird-cpp
moveForward();
moveForward();
turnLeft();
moveForward();
moveForward();
turnLeft();
while (notFinished()) {
  moveForward();
}

12. 
while (notFinished()) {
  moveForward();
  turnLeft();
  moveForward();
  turnRight();
}

13.
turnRight();
moveForward();
turnLeft();
while (notFinished()) {
  moveForward();
  turnRight();
  moveForward();
  turnLeft();
}

14.
moveForward();
moveForward();
while (notFinished()) {
  if (isPathLeft()) {
    turnLeft();
  }
  while (notFinished()) {
    executionInfo.checkTimeout(); if (executionInfo.isTerminated()){return;}
    moveForward();
  }
15.
moveForward();
moveForward();
moveForward();
turnRight();
moveForward();
moveForward();
moveForward();
moveForward();
if (isPathRight()) {
  turnRight();
}
while (notFinished()) {
  moveForward();
}

16.
while (notFinished()) {
  moveForward();
  if (isPathLeft()) {
    turnLeft();
    moveForward();
  }
}

17.
while (notFinished()) {
  moveForward();
  if (isPathRight()) {
    turnRight();
  }
}
