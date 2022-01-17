# Introduction

This Project is basically a vertical simulation of a lift bridge.In this project a graphical interface of a river where a bridge is connected from two sides.A train is moving one side to another by the help of a bridge.A signal light is indicating when to stop the train and when not.

# Project Summary

In the first display or window I displayed my name,department & project name.Besides this instructions for running this projcet is introduce in the bottom of the screen1.By pressing **'enter'** button the program will start and clicking **'esc'** button the program will exit.<br>
To start the animation we have to click  **'S'** button and to pause the animation we have to click **'t'**.<br>
The bridge have a lift system and it is lifting the middle portion of the bridge to make a path for the ship.While lift is moving the traffic signal trun red and train is stopped due to red signal.After passing the ship bridge came back to its orginal position and traffic signal turn green.After the signal became green train start to move and pass the bridge nicely.<br>

# Code Summary

In the main function we will set a windows sizee and then create a windows by calling **glutcreatewindows()** function.<br>
**glutreshapefunc()** will sets the reshape callback for the current window.<br>
In **mydisplay()** function multiple display will be handled by conditional logics.<br>
In **mykeyboard()** function keypress will be handled by their ascii values.Switch is used to implement multiple logic accroding to key press.<br>

Besides these many functions are called to create graphical instance.There are multiple display function like **screen1()**,**screen3()** etc.<br>
In **screen1()** function I introduce myself & my projcet instructions.<br>
In **screen3()** there will be a window which will appeare in the last to say thank you.<br>
There is a function called **water()** to create graphical view of blue water.Like these multiple function like **line()**,**base()**,**earth()**,**pillers()**,**bridge()**,**light()** are called to create each element in the window.<br>

# Link to demo video

Click [here](https://youtu.be/5V6fhflBE3w) to see demo video.

# Required tools to install for running this project

**glut,codeblocks**

