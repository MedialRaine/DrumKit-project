# DrumKit-project

### In this project we have been doing an approachment to the DOM, we create a little app for using the events of the keyboard and the mouse.

### We use the DOM for holding the items with class drum on a variable called numberOfDrumButtons, once we already got that then we use a for loop for iterating on the lenght of the variable, on each iteration we are gonna add event listener an all the buttons of the drum class, and we create a function for when it's clicked, inside we are gonna make it sound and make an animation each time it's clicked.

### After we just add an event listener for the key strokes, we use the event as a parameter, and each time that the event happen then, we make a sound and the animation of the button.

#### Also we make a a function for making the sound, for that as a flux control statement we use a switch, so like that each time we choose one of the letters then we can reproduce an specific sound.

#### Lastly we make the function of animation, in which use as a parameter the current key, and the we use the query selector for choosing the current key, once is pressed or clicked, then we add to the class list a class called "pressed", and for givinf the animation we use the setTimeout function for removing the "pressed" class after 1000 miliseconds.

A preview of the project:

https://medialraine.github.io/DrumKit-project/
