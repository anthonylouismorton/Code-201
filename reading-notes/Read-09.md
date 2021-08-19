
## ***Duckett HTML Book***
 
### Chapter 7: “Forms” (p.144-175)
 
- Form elements can be used to collect user information
- Forms need two pieces of information so that the server knows how to store the information; name and value
  1. Name - the attribute attached to the input tag where a user will provide information. The name is essentially a label invisible to the end-user the tells the server the input's name
  2. Value - the attribute attached to the input tag where a user will provide information. The value is the actual user input
  
- There are several input types: textbox, text area, radio buttons, etc. Multiple selections can be made per input type if desired
- A textbox can also have validation messages that prompt user if their selection meets the input criteria. For example, if it is a name textbox a validation message could appear if a user attempts to input numbers

### Chapter 14: “Lists, Tables & Forms” (pp.330-357)
- Lists can be provided different styling attributes. decimal, lower-alpha, and used to change how a list is numbered using the list-style-type property
- Tables can be styled in many ways. Each row may have its own stylings such as background color, font-weight, color, alignment, and many others
- empty cells can also be styled so that a gap or empty space does not appear in the middle of a table. This is accomplished

## ***Duckett JS book***

- Chapter 6: “Events” (pp.243-292)
- Events occur when the browser or the user performs some sort of action on the browser such as the page loading or the user clicking a button
- JS can be programmed to person an action when these events occur. For example. clicking on a button can prompt the script to make a pop-up appear with a message
- There are several types of events and sub-events which can include the following:
  1. UI Events - Occurs when the user interacts with a browser
  Keyboard Events - Occur when the user interacts with their keyboard
  Mouse Events - Occur when the user interacts with the mouse
  Form Events - Occur when the user interacts with a form on a web page

- There are three ways to bind an event to an element:
  1. HTML Event Handlers: These attributes were introduced in an early version of HTML that was added to elements that performed an action when the event occurred:
    *&lt;<a onclick="hide()"&gt;* this event handler would call the hide function
  2. DOM Event Handlers: Similiar to HTML Event Handlers, but separates JS from HTML. The main drawback is that DOM Event Handlers can only perform one function
  
  3. DOM Event Listeners: These are the preferred method of handling events. Event Listeners function similar to event handlers, but now multiple functions can occur when an event occurs.
