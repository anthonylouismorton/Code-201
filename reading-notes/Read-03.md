
# Class 201 Reading Notes: Read-03


## ***Duckett HTML Book***

### HTML Chapter 3: “Lists” (p.62-73)

- Three types of lists: Ordered, Unordered, and Definition
- Ordered lists are displayed using a numerical system
- Unordered lists are not numbered, but use a bullet style system
- Definition lists define terminologies

**Ordered List Syntax:** 

&lt;OL&gt;

  &lt;LI&gt; Candy &lt;/LI&gt;
  
  &lt;LI&gt; Soda &lt;/LI&gt;
  
  &lt;LI&gt; Popcorn &lt;/LI&gt;
  
&lt;/OL&gt;

**Output:**

1. Candy
2. Soda
3. Popcorn

**Unordered List Syntax:** 

&lt;UL&gt;

  &lt;LI&gt; Candy &lt;/LI&gt;
  
  &lt;LI&gt; Soda &lt;/LI&gt;
  
  &lt;LI&gt; Popcorn &lt;/LI&gt;
  
&lt;/UL&gt;

**Output:**

- Candy
- Soda
- Popcorn


**Definition List Syntax:** 

&lt;DL&gt;

  &lt;DT&gt; Candy &lt;/DT&gt;
  
  &lt;DD&gt; A tasty treat usually made out of sugar or chocolate  &lt;/DD&gt;
  
  &lt;DT&gt; Soda &lt;/DT&gt;
  
  &lt;DD&gt; A sugary drink made with syrup  &lt;/DD&gt;
  
  &lt;DT&gt; Popcorn &lt;/DT&gt;
  
  &lt;DD&gt; Made from heating corn until it pops. Usually mixed with butter and/or salt  &lt;/DD&gt;
  
&lt;/DL&gt;

**Output:**

Candy

A tasty treat usually made out of sugar or chocolate 
   
Soda

A sugary drink made with syrup
  
Popcorn
  
Made from heating corn until it pops. Usually mixed with butter and/or salt

### Chapter 13: “Boxes” (pp.300-329)
- Elements are treating as boxes. Without any styling boxes are only the size of the content held within the box
- CSS can be added to change the size of boxes. Height, width, padding, margin, border, and color (background and border) are a few of the stylings that can be assigned to boxes
- Boxes can be treated as inline or block elements
  **block elements occupy the entire width (line) of the page**
  **inline elements are only as large as the content within or the width specified. multiple inline boxes can occupy the same line**
  **inline elements can be turned into block elements and block elements can be turned into inline elements**

## *Duckett JS Book*

### Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)
- Arrays can be thought of as lists
- Items in an array are automatically numbered (indexed) in the order they are put into an array starting with zero

**Syntax:**
> var hockeyteams;

> hockeyteams = ['Coyotes','Ducks','Kings'];

**numbering:**

Index      Value

0         Coyotes

1         Ducks

2         Kings

- items can be added, updated, deleted, or read (crud) from an array

### Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)
- Conditional statements all for code to make a decision on what to do next depending on a condition
- for, while, and do, are loops that check conditions and make a decision accordingly
- Comparison operators are used in loops to compare two different outcomes:

**===** means strictly equal to

**!==** means not equal to

**<** means less than

**<=** means less than or equal to

- switch cases compare a value to multiple outcomes and allow the use of a default value if none of the outcomes explicitly stated are met



