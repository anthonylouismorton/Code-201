## ***Duckett JS book***

### Ch. 10, “Error Handling & Debugging (pp.449 - 486)”
- Fun fact: The word debugging, in regards to programming, originates from 1947 when engineers found a moth inside of their computer at Harvard that was causing consistent errors (https://www.nationalgeographic.org/thisday/sep9/worlds-first-computer-bug/)
- Debugging now means finding errors within code
- The console can be used to help errors. A console.log function is a tool that should return a programmer information on a certain function, method, object, or line of code to determine if they are returning the proper information. Depending on the error, the console will show on which line of code an error is occurring
- JS has 7 different errors that create an error object that displays the line number and description of the error (pp.486)
- Try(), Catch(), and Finally(), are methods within JS that can also be used to find errors within code
  1. Try(): Try() is used first when using these methods. Try() tells JS to try and execute code
  2. Catch(): Catch () is used after try. Catch(exception) tells JS to run an alternative set of code if an exception occurs
  3. Finally(): Finally() is the last step and is not required. Finally() will run whether the Try() succeeds or fails. Finally() ensures that code will always run if an exception occurs

