Applet-Game-Wrapper
===================

A primitive wrapper class that takes the boilerplate out of games made with applets. Intended for basic users and/or small projects. It was written with the goal of being incredibly simple to use and that even the newest of users will be able to understand it. At the same time the source code is released in .java form to be looked at as a teaching tool for certain basic concepts in game programming (such as graphics buffering).

Short Tutorial:
===================

All you have to do to get this project to run is download the directory of files and create a file called Game.java in the same directory. In the class be sure to include the line public class Game implements GameEngine. That's it! You don't need to remember anything else because the compiler will point out that you have forgotten to do it.

Other Notes:
GameHandler.setSize(int width, int height) - Sets window size (don't use this on realease, use html file. However this is still useful for debugging in IDEs like eclipse. 
init() - Functions like your normal applet init would.
render(Graphics g) - All graphics code belongs here
update() - Game code (AI, Collisions Checks, Spawning, etc)
keyPressed(int c) - all keyboard input will be send here. The ID # of keys pressed will be sent here. Just use if staements, switch statement, etc to go through possible combos. Use KeyEvent.VK_ and the key you are looking for. This is much easier than memorizing the id numbers for all the keys. 
