# Obstacle-Avoiding Robot

A small robot car that drives forward, detects obstacles with an ultrasonic sensor, then stops and turns to avoid them. Built for the Applied Robotics and AI Project (BEng Robotics and AI, University of Hertfordshire).

**Author:** Narayana Moorthy Chindhanaiyalan (Student ID: 3554rrea)

## Project goals
- Read distance from an ultrasonic sensor
- Control two DC motors through a motor driver
- Avoid obstacles automatically

## Hardware
- Arduino Uno (or ESP32)
- HC-SR04 ultrasonic sensor
- L298N motor driver
- 2 DC motors, chassis and battery pack

## Repository structure
```
code/    Arduino sketches
docs/    Notes and documents
```

## Getting started
```
git clone https://github.com/sinegan-ux/obstacle-avoiding-robot.git
cd obstacle-avoiding-robot
```
Open `code/obstacle_avoid.ino` in the Arduino IDE and upload it to the board.

## Git workflow
- `main` holds stable, working code.
- New work is done on a feature branch, for example `feature/sensor-reading`.
- Changes are merged into `main` through a pull request on GitHub.

## Commands used
```
git clone <url>            # download the repository
git status                 # see what changed
git add <file>             # stage changes
git commit -m "message"    # save a snapshot locally
git push origin <branch>   # upload to GitHub
git pull origin main       # download new commits
git checkout -b <branch>   # create a branch
```

## Add vs Commit vs Push
- **Add** moves changes into the staging area.
- **Commit** saves the staged changes as a snapshot in the local history.
- **Push** uploads local commits to GitHub.

## Project management
Tasks are tracked on a Trello board linked to this repository:
https://trello.com/b/ka62jln2/my-trello-board
