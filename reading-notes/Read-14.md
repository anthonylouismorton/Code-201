# Read: 14a - CSS Transforms, Transitions, and Animations

## Transforms
- Transform is a new CSS property that can be used as an aternative way to style html elements
- Transform comes with multiple vendor prefixes so that it can be used on all browsers
- Transforms allows for two-dimensional tranforms or three-dimensional transforms
- Translate is a value simliar to relative positioning that allows an element to be moved without interrupting the normal flow of a document
- Perspective is needed in order to transform an object in 3D. Perspective is similiar to a vanishing point and that is how the object is changed from 2D to 3D

## Transitions & Animations
- Transition is new to CSS3 and allows the an element to change in appearance from one state to another without the use of flash or javascript
- Animation is new to CSS3 as well. However, unlike transition, Animation allows an element to have multiple points of transition instead of transitioning from one point to another
- These stylings need to know when to occur, so the use of pseudo-classes (:hover, :focus, :active, and :target) is best way to identify when transitioning should occur
*Example transition CSS*
>.box {
>  background: #2db34a;
>  transition-property: background;
>  transition-duration: 1s;
>  transition-timing-function: linear;
> }
> .box:hover {
>  background: #ff7b29;
> }
