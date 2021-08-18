# Class 201 Reading Notes: Read-08
 
## ***Duckett HTML Book***
 
### HTML/CSS book, Ch. 15, “Layout”
 
- Div elements are similar to section elements. They group together sections on a page and make it easier to adjust the positioning of elements
- Browsers display normal flow (top to bottom) unless you explicitly set an element to display an element in a certain position. Positioning is the property for accomplishing this and positioning types include:

1. Static: All HTML elements are static by default and display with the normal flow of a page
2. Relative: relative positioning allows you to adjust an element's position on the screen left, right, up, and down. Other elements will not fill in the gap left by the element
3. Fixed: A fixed element will always appear on your screen (viewport) in whatever position you designate. If you specify an element to stay at the bottom of the screen, it will stay there even if you scroll down the page
4. Absolute: similar to fixed, absolute elements will anchor to their ancestor element. They stay fixed in one position within their ancestor element and can overlap other elements within their ancestor element

- The float property allows a user to move elements left or right on a page and can be used to make columns
- Pages can have fixed sizes or they can adjust according to the viewport size
- A grid system can be used to create the layout of a page
- HTML pages can use multiple CSS files. A reset page can clear all formatting that comes automatically with an HTML page. Then another CSS file can add the desired formatting. The CSS files are rendered in order, so a reset file would need to be listed first or it will clear any additional formatting you apply to a page
