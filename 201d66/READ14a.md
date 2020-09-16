
# 201 d66
# Read14a.md
**Reading notes and Repo updates from an aspiring WebDev.**
[Type-copy](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
[Type-copy](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

## Reading14a
### Transitions and Animations
The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.
The actual syntax for the transform property is followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
  div {
    -webkit-transform: scale(1.5);
       -moz-transform: scale(1.5);
         -o-transform: scale(1.5);
            transform: scale(1.5);
##### **2D Rotate** 
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically.
**HTML example**
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
**CSS example**
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
##### 2D Scale
Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
##### HIGHLY RECOMEND for 3D:
[notes](https://www.webkit.org/blog-files/3d-transforms/transform-style.html)

### CSS - Transitions
For a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes. There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition




### Article: “6 Reasons for Pair Programming”
1. so you have extra eyes.
2. so you have extra hands.
3. so you have extra brains.
4. so theres a higher statistical chance you'll have some "sense" between the two assumed huemans. 
5. see reason 6.
6. see reason 1. (this is a loop and call back.HOLLAH!)

