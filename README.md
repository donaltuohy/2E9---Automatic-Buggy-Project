# 2E9---Automatic-Buggy-Project

The goal of the project was to design a buggy which would follow a black line around a track. 
It could detect checkpoints through an IR sensor located on top of the buggy and detect obstacles 
using an ultrasonic sensor located on the front.
Xbee Modules were used for communication. 

The project consisted of two parts:
<ol>    
    <li>A C# console application which sent commands and recieved and parsed conformation messages.</li> 
    <li>An Arduino Uno board attached to a buggy which recieved and parsed commands and drove the buggy accordingly.</li>
</ol>
