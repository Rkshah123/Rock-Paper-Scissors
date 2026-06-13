Rock-Paper-Scissors Battle
About the Project

Rock-Paper-Scissors Battle is a JavaFX-based graphical simulation where Rock, Paper, and Scissors objects move around the screen, collide, and battle according to the classic game rules. The simulation continues until only one type remains as the winner.

Technologies Used
Java 17
JavaFX 17
Maven
JavaFX Controls
JavaFX Media
AnimationTimer
Canvas & GraphicsContext
Java Collections & Streams
Features
Smooth object movement and animations
Collision detection and battle mechanics
Visual spark effects during battles
Sound effects on collisions
Play, Stop, and Restart controls
Real-time counters for Rocks, Papers, and Scissors
Automatic winner detection
Game Rules
Rock crushes Scissors
Scissors cut Paper
Paper covers Rock

When two objects collide, the losing object is removed from the simulation.

How It Works
The game starts with:
30 Rocks
30 Papers
30 Scissors
Objects move randomly across the game area.
When collisions occur, the winner is determined using Rock-Paper-Scissors rules.
Visual effects and sounds are triggered during battles.
The simulation ends when only one object type remains.
Project Structure
src
├── main
│   ├── java
│   └── resources
│       ├── images
│       │   ├── rock.png
│       │   ├── paper.png
│       │   └── scissors.png
│       └── sounds
│           └── boom.wav
Requirements
Java 17 or higher
Maven 3.8+
JavaFX 17
Running the Project
Clone the Repository
git clone <repository-url>
cd Rock-Paper-Scissors-Battle
Run with Maven
mvn clean javafx:run
Run from an IDE
Import the project as a Maven project.
Ensure Java 17 is configured.
Build the project.
Run the main application class.
