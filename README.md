# TeamMatrix

# Team members:

David Kelly, Kulpreet Singh, Afoke Abogidi, William Hoke.

# Getting Started

How to run the game

1. Extract Matrix.zip to a new folder.
2. Run Matrix.exe
3. On the Menu select "Start Game"
4. Once the game has started you will see a player ship. The ship has 8 way movements using the arrow keys.
5. To fire bullets, press the "F" key
6. To score points, kill the enemies. The smaller enemies are worth 1 point, flying enemy 5 points, Midboss 10 points and final boss 15 points.
7. The game will end as follows: you loose all player lives, come to the end or pressed "Esc" to exit.

# Technical details:

# Storage platform: https://gitlab.eecs.wsu.edu/

# Repository: https://gitlab.eecs.wsu.edu/cpts487-sp22/teammatrix

# Tools

    1. Visual Studio 2019
    2. Git for windows
    3. MonoGame 3.8

# Setup

    1. Install Visual Studio 2019.
    2. Run MonoGame.Templates.CSharp.3.8.0.1641.vsix from cmd window.
    3. Install Git: https://git-scm.com/download/win.
    4. Clone the repository using HTTPS. Copy url to buffer.
    5. Create project directory folder C:\WSUProjects\587\.
    6. Run git clone from your project directory: git clone url.
    7. To open the Content.mgcb you may have to install the mgcb-editor.  From a administrator command window run: dotnet tool install --global dotnet-mgcb-editor --version 3.8.0.1375-develop.  Run mgcb-editor and you will see the application start.  Now go to task manager and find the running app.  Right click to open file location.  Get the location and add it to the Open With... for the Content.mgcb file.  Add a new program and enter the path to find mgcb-editor-wpf.exe.  Add it and set as default.  Now when you d-click Content.mgcb, it will load into the editor.

# Change Work flow

    1. Add files to the project dir or modify them.
    2. Get the status: git status.
    3. Run git add to stage files for commit: git add.
    4. Commit files: git commit -m "message".
    5. Push files to repo: git push.

    Optionally use Visual Studio git.
