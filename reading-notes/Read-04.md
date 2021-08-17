# Class 201 Reading Notes: Read-03

## ***Duckett HTML Book***

### HTML Chapter 4: Ch.4 “Links” (pp.74-93)

- Links allow an html page to connect to an outside source
- Links can redirect a user to a new page or could be used to display external media to a page
- Links are created using the &lt;a&gt: (anchor) element  
- Examples of links include:

  1. Links to other sites: These link from your page to an external page such as Amazon, Google, etc.
  
  > &lt;a href="Google.com"&gt; Click here to go to Google &lt;/a&gt;
  
  3. Links to other pages on the same site: These link from pages on the same site such as from the Home page to the About or Contact page
 
  > &lt;a href="About.html"&gt; About Us &lt;/a&gt;

  5. Email Links: This will start up a user's email program and will address an email to an that you specify

  > &lt;a href="mailto:johndoe@gmail.com" &gt; Click here to send the site creator an email &lt;/a&gt;
  
  7. Open link to a new window: When a user clicks on this link it will open in a new window
  
  > &lt;a href="Google.com" target="blank"&gt; Click here to open Google in a new window &lt;/a&gt;
  
  8. Link to specific part of a page or different page: This link will take a user to a certain part of the current page or another page on a site

  > &lt;a href="#summary"&gt; Summary &lt;/a&gt

### Chapter 15: “Layout” (pp.358-404)
- Div elements are used to group similar sections together on a page. It is good practice to contain all elements within a div or other section like tags
- Relative, fixed, and absolute css styling is used to determine where an element will be displayed on a page. Otherwise the page will display with normal flow (top to bottom)
  
  > &lt;footer"&gt By adding fixed and bottom styling we can allow the footer to always appear at the bottom of the window even if you aren't scrolled to the bottom of a page &lt;/footer"&gt
  > footer {position: fixed; left: 0; bottom: 20px; width: 100%; }
  *This CSS code block places the footer 20 pixels up from the bottom of the page at all times*
 
- The float property when added to an element will move the element to the left or right of a page
- Multiple CSS pages can be used for an html page. This is useful when creating
- Partial pages can also be created using html. Partial pages allow for a basic template that will show up on multiple pages. This is useful as you don't have to recode multiple pages when you make changes to an element such as a nav bar that will appear on every page
- CSS framework creates grids to layout a page and creates multiple column layouts

## *Duckett JS Book*

### Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
**Functions**
- Functions allow a block of code to perform a certain task.
- Functions can be called multiple times and prevent the need to duplicate code
- A function can generate statements when a user clicks an item on a page or ask the user for two numbers and perform multiplication on those numbers

*Declaring a simple function*
> function helloWorld() { document.write('Hello world!');

*Calling a simple function*
> helloWorld();

*Function taking multiple values and returning a single value*
> function multiply(num1, num2) {var multiply = num1 * num2; return multiply}

*Calling multiple value function*
> multiply(10,20);

## *Article: “6 Reasons for Pair Programming”*
https://www.codefellows.org/blog/6-reasons-for-pair-programming/

- pair programming is the practice of two people programming together
- usually consists of two people, driver and navigator:
1. the driver is the individual who is physically typing code
2. the navigator does not perform typing, but assists in identifying typos and bugs, looks at the "big picture", and looks for solutions and documentations to assist the driver

**6 reasons to use paired programming**

1. Efficiency: Paired programming takes slightly longer, but creates higher-quality code. Programmers can also identify solutions quicker. Pair programming also increases teamwork and team communication.
2. Engaged Collaboration: Working with another programmer keeps both programmers engaged and on track.
3. Learning from fellow students: Working together helps people learn new problem-solving skills as everyone works differently. Less experienced developers learn new skills using this technique, and skilled developers can increase their own understanding
4. Social Skills: Paired programming increases social skills. communication and social skills are "soft skills", but can be just as important as technical skills. Communication is key!
5. Job Interview Readiness: Paired programming can assist in preparing for an interview. Technical interviews work similar to paired programming. An employer will give you a challenge and watch you build a project, algorithm, method, feature, etc. They will most likely ask you to explain your "logic" and this is very similar to paired programming
6. Work environment readiness: Paired programming is part of many work environments. In the "real world" you will most likely perform paired programming or some sort of collaboration on a project. By learning this skill now, it shows an employer that you have one less skill to learn and makes you a more "hirable" candidate.

