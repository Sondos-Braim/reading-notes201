# Read10
## Error handling and debugging
It is common to face some errors in the process of writing your code using JavaScript. However, there are different methods that you can use to help you locate those errors and to debug your code.

First of all, you should be familiar with the console log and the developer’s tools in the browser. Secondly, you should familiarize yourself with the most common problems so that you can avoid them when you are writing your code such errors might be very basic such as upper and lower cases or extra letters or something that has to do with the data types. Finally, you should write your code in a way that it will deal with any potential error that might happen in the future and not to write it in any way that you find easy.

JavaScript has a certain order in which it executes the codes, you should also be familiar of the way that the language works and what it executes first in order to be able to write a code that has no bugs.

JavaScript is interpreted one function at a time. If it finds a call for another function, it goes to the other function and when it finished it will go back to its place.

Each time a script enters a new execution context, there are two phases of activities: firstly, it will prepare the codes, and then it will execute.

### Scoping

Within the JavaScript execution context, it will only assign the variables to its context so if a variable is declared inside of a function, it cannot be used outside of this function. However, if there is a variable that is declared outside the functions, it will be considered as a global variable that can be used in were on the file.

There are some statements that can be done to handle the error in your codes which are: Try, Catch, and Finally. These three are connected so when you write something in Try, it will give you an exception. And then it will go to catch unless you do a return or a break then it goes directly to the Finally.

When there is an error in your code, the text editor will point them out for you indicating what have you done wrong. If the editor cannot find the errors, then you can use the console in the developer’s tools in the web browsers. The console is very helpful for debugging since it tells you exactly what your errors are. You can also enter more than one message into the  console as a group to see the result in one time.

To know where exactly the problem occurred, you can use the breakpoints that stops the execution of the code at a certain point so that you can check the values and tell what went wrong.

The debugger keyword is used to indicate a breakpoint and it will work as a breakpoint but it is necessary that you remove them before your page goes live so that it can work when the user views it.

When you have a bug in your error you should go back and fix it manually or if it is an error that you can’t control, then use the handling exceptions mentioned above.

