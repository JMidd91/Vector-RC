# Vector-RC
Remote Control App for Anki Vector

This is a Flask web app to control Anki's Vector robot - https://www.anki.com/en-gb/vector

this app is based on their app that ships with the SDK - https://github.com/anki/vector-python-sdk/tree/master/examples/apps/remote_control

I am just using their app to edit and learn and create my own in the process.

So far the controls are the same in mine as theirs, except I have added H to tell vector to go home.

screenshots - 

https://github.com/JMidd91/Vector-RC/blob/master/_screenshots/1.png.

https://github.com/JMidd91/Vector-RC/blob/master/_screenshots/2.png.


Id like to point people to a more developed app that gave me insiration - 

  https://github.com/rmountjoy92/VectorCloud


<h1><b>Todo</b> - </h1>

  <h2><b>facial recognition</b> -</h2> on hold as there is bug in Vector SDK preventing progress. - https://forums.anki.com/t/face-id-is-wrong-in-sdk/28524/2
  
    - add squares around faces detected
    
    - add name tags next to known face when detected
    
    - add expression tag next to detected face
    
    
  <h2><b>audio</b> -</h2> on hold due to SDK bug. - https://forums.anki.com/t/audio-processing-and-events-in-the-sdk/24484/15
  
    - add output from Vectors mic to pc
    
    - add markers to show direction of detected audio
    
    - possibly add function to allow user to speak into pc mic and then vector can repeat what is said.
    
    - see if its possible to add remote voice control for vector via pc mic
    
  
  <h2><b>speedometer</b></h2>
    
    - not sure aeronautical colouring of needles is clear enough. needs better ux 
    
    
  <h2><b>Other</b></h2>
    
    - think of way to display other items such as:
      
      - gyro info
      
      - nav map ( possible minimap? )
      
      - proximity
      
      - photos
      
      - network info
      
    - create a menu
    
      - add buttons to toggle HUD elements 
      
      - add key map
