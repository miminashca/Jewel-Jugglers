
# Gem-Sorting Galore

## Description

**Gem-Sorting Galore** is an engaging game that centers around sorting different types of gems using a tilting joystick. This game was my second significant project, completed during the third term of my first year in college. I participated in this project as a Game Engineer, using Arduino and C# to develop the game, which leverages tilting joystick controls for an immersive user experience.

### Background
In **Gem-Sorting Galore**, players stand in front of a sorting conveyor belt where gems of different colors and shapes appear. The task is to tilt the joystick to guide each gem into the correct bin before it reaches the end of the conveyor. The game features a timer and a score system, with points awarded for each correctly sorted gem and penalties for mistakes. The objective is to sort as many gems as possible before the timer runs out.

### Gameplay
The main gameplay involves:
- **Sorting Gems**: Direct each gem into the correct bin by tilting the joystick.
- **Conveyor Belt**: Gems appear on a conveyor belt, and players must act quickly to sort them before they reach the end.
- **Timer and Scoring**: Earn points for correctly sorted gems and avoid penalties for mistakes. The game ends when the timer runs out, and success is measured by the number of gems sorted correctly.

### Development Contributions
In this project, I worked extensively on the control system and scoring logic. My responsibilities included:
- **Scoring Logic**: Programming the conditions under which gems were considered correctly or incorrectly sorted, based on their color and shape.

### Reception
**Gem-Sorting Galore** was well-received by my peers and instructors, earning praise for its innovative use of joystick controls and engaging gameplay mechanics. The project was a valuable learning experience, allowing me to delve deeper into hardware integration and real-time control systems.

## Project Structure

### Root Directory
- **GameArduino/**: Contains the main project directory.
  - **.DS_Store**: macOS file for folder attributes (can be ignored or deleted).
  - **game/**: Contains the game files.
    - **gameFolder/**: Main game folder.
      - **GXPEngine.sln.DotSettings.user**: User settings for the solution.
      - **.vs/**: Visual Studio specific files.
      - **GXPEngine/**: Contains the source code and related files for the game engine.
        - **obj/**: Directory for object files and intermediate outputs.
        - **.DS_Store**: macOS file for folder attributes (can be ignored or deleted).
        - **UIBatteries.cs**: Source file for UI batteries.
        - **bin/**: Directory for binary files and compiled executables.
        - **Box.cs**: Source file for box class.
        - **RotationReader.cs**: Source file for reading rotation.
        - **Controller.cs**: Source file for the controller class.
        - **Creature.cs**: Source file for the creature class.
        - **GXPEngine.csproj**: C# project file for the game engine.
        - **LifeCounter.cs**: Source file for the life counter.
        - **Gem.cs**: Source file for the gem class.
        - **GXPEngine/**: Additional source code for the game engine.
        - **app.config**: Configuration file for the application.
        - **MyGame.cs**: Main game file.
        - **Player.cs**: Source file for the player class.
        - **ArduinoControls.cs**: Source file for Arduino controls.
        - **Level.cs**: Source file for the level class.
        - **PressButtonText.cs**: Source file for press button text.
        - **HUD.cs**: Source file for the HUD (heads-up display).
      - **.gitignore**: Specifies files and directories to be ignored by git.
      - **nano33iot_imu_madgwick/**: Contains Arduino-related files.
      - **changelog.txt**: Contains the changelog of the project.
      - **.git/**: Git repository containing version control information.
      - **GXPEngine.sln**: Visual Studio solution file for the project.
      - **.idea/**: Contains IDE-specific files.

## Getting Started

### Prerequisites
- Visual Studio or a compatible C# development environment.
- Arduino development environment for hardware integration.

### Building the Project
1. Clone the repository or download the project files.
2. Open the `GXPEngine.sln` solution file in Visual Studio.
3. Build the solution using Visual Studio (Build > Build Solution).

### Running the Game
- After building the solution, navigate to the `bin` directory and run the executable.
- Ensure the Arduino hardware is properly connected and configured.
