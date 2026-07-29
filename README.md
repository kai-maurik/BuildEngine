<h1>BuildEngine</h1>

<p>An open source 2D Java game library</p>

> Note: This project is discontinued and preserved for archive. I build this when I was 14 years old, so it's nostalgia for me :)

<img width="1282" height="752" alt="image19" src="https://github.com/user-attachments/assets/abe8eb7f-ecdb-4c9b-848c-6a7ece965607" />

> This is a game made in the engine

BuildEngine makes programming in Java a lot easier by providing all sorts of utilities and a robust understandable structure. This way you can focus on programming your game, and BuildEngine takes care of the boring stuff.

<h2>Features</h2>

<h3>The Stage is yours</h3>

Build like a theatre play, naming conventions are intuative. Easely add your own components.

<h3>Rendering</h3>

Rendering made easy so you don't have to worry about rotation calculations or your graphics card.

<h3>Collisions</h3>

With a simple way to test for and resolve collisions using the SAT method.

<h3>Other Utilities</h3>

Math, Asset loading, animations, sounds, file I/O, inputcapturing, debug and timed events.

<h2>Class Architecture</h2>

> BuildEngine uses an implementation increasingly popular ECS system. However, because BuildEngine is written in java, and some optimization features of ECS don’t apply to java, the engine functions a bit differently from normal ECS systems. You can think of BuildEngine’s naming convention as if the player were attending a theater show. In this theater show, there is a Stage. The theater show (the game) is being presented on this stage, divided into scenes. Each scene has actors who play in the scene, and directors directing the scene; telling the actors what to do. So if you ever get confused by a name in BuildEngine, think back to this example. Now, layed out here is a diagram of the engine’s core structure.
<img width="1000" height="810" alt="ef77499debfc449c18aaa2178a8a7a30_1000x810_fit837a" src="https://github.com/user-attachments/assets/edbda225-a3f4-4920-97b3-afa6f77cc36d" />

<h2>Chess</h2>

<i>A build engine project</i>

A multiplayer experience of Chess. This project uses BuildEngine's architecture, rendering, asset utility's, sound and collission system.
<img width="1735" height="931" alt="1f10c23cb3389cba06dabc63770bc0d4_fit837a" src="https://github.com/user-attachments/assets/7d16d7d8-5a47-44c1-aa26-7a9bf68a1417" />
<img width="915" height="547" alt="e8e532a74075de35d4a7ce3474861ca8_fit837a" src="https://github.com/user-attachments/assets/f0036c64-191b-4160-848f-3e4780760c32" />

<h2>Get started</h2>

To get strated, add your preffered build to a new java project in your favorite IDE. See the IDE documentation on how to add a library. Bellow is a quick example of a simple scene to get you started.

1. Download your prefered version of BuildEngine.
2. Unpack the Zip file.
3. Create a new empty Java project in you IDE of choice.
4. Add the BuildEngine.jar file to your project dependencies, or as a library.
5. Try writing the code bellow.
6. Run your program. You should now have a moving character.

If no auto-completion shows up, you probably have not added the BuildEngine jar correctly. Try again by following a tutorial for your IDE. Also make sure you are running the latest Java SDK, otherwise some features may not work as intended.

This version of the engine uses the build in java graphics library (AWT) for rendering. This version is the most stable.
Features:
 - A collection of core abstract classes based on ECS, capable of creating any game (see core-architecture).
 - Supports animations, custom rendering, but also an elaborate implementation for default rendering.
 - An advanced collision system, using SAT. Also a basic physics implementation. Both are customizable.
 - <i>A lot</i> of pre-made Directors and Components. 
 - Java rendering using an custom advanced Draw class, handling resizing, unit scaling and rotation.
 - Audio like sound effects and music handling.
 - Configuration file I/O, for easy writing and retrieving data.
 - The input system is capable of detecting press, hold and release for key and mouse plus many more features.
 - A small math library, containing full Vector2 clases, shapes and transforms used for the collision system.
 - Static event scheduler, so you can start timed or repeating events anywere.
 - Asset handling, like reading and saving in chache.
 - Easy and fun to program in :)
