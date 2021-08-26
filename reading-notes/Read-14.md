# 14a - CSS Transforms, Transitions, and Animations

## Transforms
- Transform is a new CSS property that can be used as an alternative way to style HTML elements
- Transform comes with multiple vendor prefixes so that it can be used on all browsers
- Transforms allows for two-dimensional transforms or three-dimensional transforms
- Translate is a value similar to relative positioning that allows an element to be moved without interrupting the normal flow of a document
- Perspective is needed in order to transform an object in 3D. Perspective is similar to a vanishing point and that is how the object is changed from 2D to 3D

## Transitions & Animations
- Transition is new to CSS3 and allows the element to change in appearance from one state to another without the use of flash or javascript
- Animation is new to CSS3 as well. However, unlike transition, Animation allows an element to have multiple points of transition instead of transitioning from one point to another
- These stylings need to know when to occur, so the use of pseudo-classes (:hover, :focus, :active, and :target) is the best way to identify when transitioning should occur
*Example transition CSS*
>.box {
>  background: #2db34a;
>  transition-property: background;
>  transition-duration: 1s;
>  transition-timing-function: linear;
> }
> .box:hover {
>  background: #ff7b29;
> }
- This example CSS would change the background of the box element when it hovers over and the transition occurs over 1 second (https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
- vendor prefix should be added to transitions and animations to ensure that they are supported on all browsers
- transition-property can be used to target certain properties within an element, otherwise, all will be targeted
- transition properties can be applied to most CSS styling such as border-color, font-size, color, etc
- @keyframes is used for animations and it is where a user will set multiple breakpoints for a transition. This is required when transitioning is from more than two points
- animations need a name and duration in order to function. Delay and timing-function can also be added to animations
- iterations can be used to determine how many times an animation shall occur and they are allowed to occur an infinite amount of times
