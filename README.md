Author Alec S
Conway Game of Life
instructions:
javac Conway.java
javac BoardButton.java
java Conway
click on squares to activate them. Then, click step to see each generation, or click animate to see steps in succession. to stop, click
stop animation and clear. while, animating, you can still click on squares to bring them to life. click on squares to deactivate them as well. 
if you've cleared, and everytime you click on a square, it dissapears, you still have a timer going, click on stop animation then continue.
questions?

You can also run java -jar Conway.jar to run the java executable with default settings.

The current implementation is limited space, meaning once a bit reaches the edge of the board, it's as if it reaches the edge of space.
if you want to change the limited space, edit "dim" in Conway.java. If you want to change to animation speed, edit "speed" in Conway.java
Questions? e-mail linuxbash8@gmail.com
