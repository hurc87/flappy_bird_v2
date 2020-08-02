# flappy_bird_v2

Tutorial using the following link on [youtube](https://www.youtube.com/watch?v=gxHcW84izz0)

## Key Learning

### css - top

This gives us spacing between the top of the parent element and our element.

### css - position: absolute;

This means our child element is positioned relative to its parent container, based on the parents elements dimensions and position.

### css - position: relative;

This means the element will be positioned relative to its normal position.

### style.bottom

We can change the css for positioning an item in javascript by calling the element name, then style, then the css description we are wanting to change. 

eg. 

        element.style.bottom = 50px

### keyup vs keydown

The key up event will be triggered when you fingers leaves the button vs the keydown event which is triggered when you first press the key.

eg. 

         document.addEventListener('keyup', control)

