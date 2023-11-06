# qhua6277_9103_Individual_tut02

##**Qinghui's individual work**
Added animation based on user input for background curves to the group code.

##**User input**
Click on the screen to see the flow of the sky and the waves. 

When clicking, the closer the mouse is to the left side of the screen, the slower the flow is, while the closer it is to the right side, the faster the flow is. There is a slight difference in the flow speed of the sky and the waves.

##**Main changes of the group code**
Add moveSpeed, moveOffset and rate. Connect the moveOffset with moveSpeed and rate, and then connect it with xoff which is an important part of the curves. These set the movement of the curves.
Add a mouseClicked function and set the moveSpeed on it to connect the mouse click with the curve move.
