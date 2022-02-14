# 152


Document Object Model.

Basically, this model or design considers web pages as documents and follows a certain structure to represent each element of this
document.

This model connects web pages (which are displayed using HTML) with programming languages such as Javascript.

This helps us to access and manipulate the element data on the web pages.

Since A-Frame is just HTML, we can control the scene and its entities using JavaScript and HTML DOM.

There is something called events and event listeners in JavaScript. 
With JavaScript events and event listeners and HTML DOM, A-Frame entities and components can be connected with one another easily.




In the Speed Racer game, we used DOM elements like button, input, and heading, as shown in the gif. Behind the scenes,
we have a defined tree-like structure for this. When a web page is loaded, the browser creates a Document Object Model of the page.

Basically, this model or design considers web pages as documents and follows a certain structure to represent each element of this document. This model connects web pages (which are displayed using HTML) with programming languages such as JavaScript.
Since A-Frame is just HTML, we can control the scene and its entities using JavaScript and HTML DOM.


There are something called events and event listeners in JavaScript. 
With JavaScript events and event listeners and HTML DOM, A-Frame entities and components can be connected with one another easily.

example:
For example, if you click on a button, and the color of the button changes, 
that means the button click event has occurred, which is listened to by an event listener, and based on that, the button color is changed.

example:
an event is created every time something happens to the elements on the webpage. For example, the most common event that you have created is the click event. Every time you click with your mouse on the web page,
some event listener responds to it. Similarly, pressing a key or starting an animation on the web page are events.

the A-Frame DOM structure. In the browser window, 
the A-Frame HTML is the document under which the  element is created; followed by that, one or more  is created.



to move the box on mouse click, we can use the addEventListener() method on the browser window element.
And then increment the moveX value only when the mouse is clicked on the screen.
The position attribute will be updated once the moveX value is incremented after the click.
************************************
 create a rocket launch simulation scene?

We can use 3D models.
When a rocket is launched, as it goes up in space, the parts of the rocket detach.
we can use multiple parts which can fall down once clicked on the screen, so instead of using a model, we can create our own shape for the rocket.

After we have got the shape, we will move it upwards. Remember how to write a component to move a box.
We can write the same component for the shape we have drawn.

we should be able to see the shape move upwards along the far view of the Earth as it goes higher and higher, right?
So we will quickly create the sphere entity for the Earth view.



Then we can write the custom component to move the camera position. How can the position of the camera be changed to have a zoom-out effect?

ans:  z-axis.

-----------------------
Finally, we will write a component and add a window click event which will make the third part of the rocket shape fall down on click. How can we do that?
ESR: By using addEventListener().

 A multistage rocket is a launch vehicle that uses two or more rocket stages. It is also known as a step rocket.

In serial staging, a small rocket is placed on top of a larger rocket. The larger one is the First Stage, and the smaller one is the Second Stage. The first stage is ignited while launching, and it keeps burning until its propellants are exhausted.

On the other hand, in parallel staging, many small first stages are strapped onto a central sustainer rocket.
All the engines are ignited at launch.
The strap-on rockets are discarded when the propellants in the strap-ons are extinguished.


--------------------------------

In the next class, we will start working on the flight simulation VR.




We will apply this component to the entire shape to move the shape altogether.


