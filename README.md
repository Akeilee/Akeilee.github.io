# Projects

The projects below were created during my time at university. <br />
Clicking on the picture will take you to its respective repository/playable game link. Each project's repository details a list of features and keybinds used. 
<br />


## Fantasy Rhythm

<a href = "https://akeilee.github.io/FantasyRhythm/"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/gameplayGif.gif" alt = "game" width = "300"></a>

<details>
<summary><strong>Click for more details</strong></summary>
<p>
Fantasy Rhythm is a short 2D game that was made for my undergraduate games development module using Unity. The main concept is to battle monsters through a rhythm game. Inspiration for it came from different rhythm games such as Dance Dance Revolution and Project Diva. This assignment demonstrates game designing and the ability to use game engines.<br /><br />   

The songs and styles chosen are aimed towards a cartoon theme as it creates an energetic and playful feel throughout the gameplay. Designs for the assets came from various video games and anime references.<br /><br />

The gameplay is arrow key inputs, in time with the rhythm. There are three different keypresses: normal, hold and double keys. Maintaining a combo will increment the multiplier score.<br /><br />

Future features would include a levelling system where you would be able to unlock more cosmetics and songs, have better treasure box loots and an increase to the player's max hp.<br /><br />

Listed below are the past prototypes for the game:<br />
<a href = "https://akeilee.github.io/Rhythm-Prototype-Initial/">Initial Prototype</a><br />
<a href = "https://akeilee.github.io/Rhythm-Prototype-Level/">Level 1 Prototype</a><br /><br /></p>
</details>

## MSc Game Graphics
<a href = "https://github.com/Akeilee/Game-Graphics"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/lighting.gif" alt = "graphics" width = "300"></a>

<details>
<summary>Click for more details</summary>
<p>
My game graphics coursework demonstrates a rendering of a graphical scene using techniques learned through my graphics module. The scene is in a cyberpunk style and made using C++ and OpenGL. It contains a large landscape with numerous graphical elements being rendered. <br /><br />

Various post processing effects have been implemented such as:<br />
<ul>
<li>Blur</li>
<li>Gamma Correction</li>
<li>Split Screen</li>
</ul>

These can be toggled with keybinds.<br /><br /> 

Lighting is created with deferred rendering and a shadow map is used for real-time shadowing.<br /><br />

In the future I would like to attempt to create reflections on surfaces by using texture mapping.<br /><br /></p>

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/5CmZtc3gN7A" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
</details>

## MSc Physics and AI
<a href = "https://github.com/Akeilee/Game-Tech"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/main.gif" alt = "physics" width = "300"></a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/urHL-WkVB7w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

For this project I developed a simple game that shows off physics and AI knowledge that I have learned throughout my game technology module. The aim of the game is for the player to navigate around a map filled with obstacles, to try and reach the finish line. They will only lose if their health reaches zero. 

The objects have used physics calculations to allow them to move. Collision detection and resolution are also implemented for objects to be pushed around and for items to be collected.

The AI uses an A* pathfinding to navigate itself towards the exit whilst collecting coins along the way. 

The most challenging part of this project was figuring out the capsule collision tests. Eventually I would like to try implement capsule vs capsule and OBB vs OBB collisions.

<br />


## MSc Game Programming
<a href = "https://github.com/Akeilee/Game-Programming-2"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/overallShort.PNG" alt = "maze" width = "300"></a>

This small program was created with C++ to demonstrate my ability to use different search algorithms to create an ASCII maze and then solve it. 

The maze uses a depth-first search algorithm with recursion to create the maze.

Each player (**P**) starting at an entrance (**E**) will take it in turns to move towards the finishing point (**F**). They each use a breath-first search algorithm to find the optimal path. Players are not allowed to be in the same place at the same time and also if another player is in the way, then the current player cannot move for that turn. 

The user is able to generate different size mazes and they are able to save these mazes to file. 

[Program without player progression](https://github.com/Akeilee/Game-Programming-1)

<br />


# Other Work

<details>
<summary>Click to expand!</summary>

<br />  
## OpenGL Shaders
<a href = "https://github.com/Akeilee/3223-Graphics-2"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/blendCube.gif" alt = "shaders" width = "300"></a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/FRGN_cY4HNw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

For this piece of coursework I was asked to create a simple scene that had different graphical shaders affect a cube in real time. I used C++, OpenGL and its associated shader language, GLSL.

Numerous shaders were used such as a: 
Geometry shader - invoked once per primitive and takes in the vertices of the cube and outputs new primitives that form new smaller cubes,
Tessellation shader - invoked once per vertex and creates new triangle primitives to distort the cube based on a heightmap, 
Lighting shader - creating a spotlight effect on the cube.
<br />
  
  
## OpenGL Graphics
<a href = "https://github.com/Akeilee/3223-Graphics-1"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/graphicsSpace.png" alt = "rasterisation" width = "300"></a>

This project shows the various graphical primitives and rasterisation techniques learned from my 3223 Graphics module. 

The coursework spec was to render a 2D space scene consisting of triangles, lines and points using C++ and OpenGL. There is usage of different depth buffer tests and alpha blending states.
<br />
  
  
## Python GUI
<a href = "https://github.com/Akeilee/Rover-Gui"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/screenshot.jpg" alt = "roverScreenshot" width = "300"></a>
  
This GUI was created during a two week sprint for the Engineering Society's entry into a tournament. The main sketch was drawn up by the design team in the society and I was then tasked with creating the home screen in python. 
  
Interactable buttons consists of the home, info, help and logo button. Clicking on them will only print to the console.

As this was my first time learning and using Python I was unable to create a more detailed GUI. For future projects, I would like to add more interactable features. 
<br />
  
  
## Website 
<a href = "https://github.com/Akeilee/1026-Website"><img src="https://raw.githubusercontent.com/Akeilee/Akeilee.github.io/main/Images/website.PNG" alt = "websiteScreenshot" width = "300"></a>
  
This interactive example website was made for my 1026 Website design coursework. 
  
It uses HTML, CSS and JavaScript. 
  
The assignment helped me develop my knowledge of the web, its client-site technologies and principles of good web design. 
<br />
	
</details>
