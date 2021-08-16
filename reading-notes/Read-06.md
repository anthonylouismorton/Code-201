# Class 201 Reading Notes: Read-05
 
## ***Duckett JS Book***
 
### Chapter 3: “Object Literals” (pp.100-105)
 
- An object is a set of variables and functions used to create a model. An object can be thought of as a template for real world itmems
- A car object would have a make, model, engine, doors, color, and transmission. An instance of this object would be a two door 1967 ford mustang with a 5.0 engine and a manual transmission
- Objects can be used to create several instances of that object and prevents code from being repeated
- Functions inside an object are called methods
- Variables inside an object are called properties. Each property must have a unique name as the name is how each property is accessed
 
 
 **Literal Notation** 
 
  > var car = {
  
  > make: 'Ford',
 
  > model: 'Bronco',
 
  > Year: '1972',
 
  > horn: function() { console.log('beep beep');
 
 
  **Dot Notation**
  
 > var carMake = car.make;
 > var carModel = car.model;
 > var honkHorn = car.horn();


 
### Chapter 5: “Document Object Model” (pp.183-242)
- Document Object Model (DOM) is how a webpage will be created and allows JS to access and update the content of a webpage
- DOM trees have four types of nodes

  1. document nodes: represents entire page
  2. element nodes: represent different elements such as paragraph tags or heading 1 tags
  3. attribute nodes: represents attributes attached to elements
  4. text nodes: represents the text held within an element
  
 - element nodes can be selected by their id or class attributes, tag name, or using CSS selector syntax (pp. 242)
 
 getElementById('genericIdname')
 
 - Nodelists are created when a DOM Query can return more than one element. displayed similar to an array and each list item will have an index
 - InnerHTML and DOM manipulation techniques allow a user to access or update the content of an element node
 - JQuery is often used because older browsers cannot properly implement DOM
