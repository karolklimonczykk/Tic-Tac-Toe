# Tic-Tac-Toe
<h2>Description</h2>
<b>Socket-based communication. Transferring data between computers connected to the network. The program implements a simple tic-tac-toe game.</b> </br></br>
<p>
The program operates in a client-server architecture, and both modules will be implemented
together:
<ul>
<li>after starting the program, the user enters the server's IP address and tries to connect
connection via the Start button: </li> 
<ul>
<li>if the server is working, connection is made and the game starts</li>
<li>if the connection is not established, the program starts in server mode</li> 
</ul>
</ul>
By default, the program creates a socket based on port 23456. The game starts at
client connection
<ol>
<li> the server is assigned an X and the client is assigned an O. When the client is connected, the user is on
the server goes into traffic making mode and the client goes into traffic waiting mode
opponent</li>
<li> the server checks whether the game has not ended (loss/draw) </li>
<ul>
<li> if yes, an appropriate message is displayed and a jump to 6 </li>
<li> if not, the player on the server makes a move by clicking in the allowed area</li>
</ul>  
<li> the server checks whether the game has not ended (win/draw)</li>
<ul>
<li>If so, the server sends the coordinate of the selected field to the client, displayed
there is an appropriate message and jump to 6</li>
</ul>  
<li>after receiving the opponent's move coordinate, the client checks whether he is playing
has not ended (loss/draw)</li>
  <ul>
<li> if yes, an appropriate message is displayed and a jump to 6</li>
<li>if not, the player on the client makes a move by clicking in the allowed area</li>
    </ul>
<li> it is checked whether the game is over (win/draw)</li>
  <ul>
<li> if not, the movement coordinate is sent to the server and jump to 2</li>
<li> if yes, the movement coordinate is sent to the server and is displayed
appropriate message and jump to 6</li>
    </ul>
<li>end of game.</li> 
</ol>
</p>
<br />


<h2>Languages and Utilities Used</h2>

- <b>JAVA</b>

<h2>Environments Used</h2>

- <b>IntelliJ IDEA 2023.3.3</b>

<h2>Libraries Used</h2>

- <b>Java Swing (GUI)</b>

<h2>Program walk-through:</h2>

<p align="center">
Creating the stiffness matrix of a beam element <br/>
<img src="https://i.imgur.com/UwhIF1S.png" width="80%" alt ="ke"  width="80%"/>
<br />
<br />
Creating a global stiffness matrix:  <br/>
<img src="https://i.imgur.com/hCmyxCE.png" alt="Global marix " width="80%"/>
 <img src="https://i.imgur.com/0L7TFOK.png" alt="KK" width="80%"/>
<br />
<br />
Applying boundary conditions: <br/>
<img src="https://i.imgur.com/WREGb5y.png" width="80%" alt="boundaryConditions"/>
<br />
 boundary conditions for given scheme: <br/>
 <img src="https://i.imgur.com/FJPPM3E.png"  alt="conditions"/>
<br />
 <br />
Solving for displacement vector:  <br/>
<img src="https://i.imgur.com/8lU3NXp.png" width="80%" alt = "displacement vector"/>
<br />
<br />
results:  <br/>
<img src="https://i.imgur.com/t5id8vp.png" width="80%" alt="plot"/>
 <img src="https://i.imgur.com/wVPcKBl.png" width="80%" alt="error"/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
