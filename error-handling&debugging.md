#  Error Handling and Debugging

## How to find the errors in your code..
We will talk about three main things :
* THE CONSOLE & 
DEV TOOLS 
* COMMON 
PROBLEMS 
* HANDLING 
ERRORS

### **ORDER OF EXECUTION**

To find the source of an error, it helps to know how scripts are processed. 

*The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run*

 for example :
![ORDER OF EXECUTION](https://www.programmersought.com/images/551/d5737970f3770fbcdceebf7240f05daf.png)

### **EXECUTION CONTEXTS**
The JavaScript interpreter uses the concept of execution contexts.

* GLOBAL CONTEXT(
Code that is in the script, but not in a function.)
* UNCTION CONTEXT(Code that is being run within a function. )
* EVAL CONTEXT (Text is executed like code in an internal function )
## **EXECUTION CONTEXT & HOISTING**
  
***Each time a script enters a new execution context, there are two phases 
of activity:***
1.  PREPARE 
 * The new scope is created 
*  Variables, functions, and arguments are created 
*  The value of the this keyword is determined .

2. EXECUTE 
* Now it can assign values to variables 
* Reference functions and run their code 
* Execute statements 

#### Understanding that these two phases happen helps with understanding a concept called hoisting. You may have seen that you can: 

• Call functions before they have been declared 

• Assign a value to a variable that has not yet been 
declared


## **UNDERSTANDING ERRORS**

If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code.

***SIMPLY ...***

If you are anticipating that something in your code 
may cause an error, you can use a set of statements 
to handle the error (you meet them on p480). 
This is important because if the error is not handled, 
the script will just stop processing and the user will 
not know why. So exception-handling code should 
inform users when there is a problem. 
## **ERROR OBJECTS**
Error objects can help you find where your mistakes are



|OBJECT         |DESCRIPTION 
| ------------- | ---------  | 
|     EvalError | Creates an instance representing an error that occurs regarding the global function eval().   |   
|      RangeError | Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range.        | 
|      ReferenceError  |  Creates an instance representing an error that occurs when de-referencing an invalid reference         |   
|    SyntaxError   |  Creates an instance representing a syntax error.       |   
|   TypeError  |  Creates an instance representing an error that occurs when a variable or parameter is not of a valid type.      |           
|     URIError | Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters.            |            
## **HOW TO DEAL WITH ERRORS**
1.  DEBUG THE SCRIPT TO FIX ERRORS.
2.  HANDLE ERRORS GRACEFULLY.

## **A DEBUGGING WORKFLOW **
Debugging is about deduction: eliminating potential causes of an error. 

    YOU CAN ASK THESE QUESTUINS 
    1.  WHERE IS THE PROBLEM? 
    2.  WHAT EXACTLY IS THE PROBLEM? 

## **HOW TO LOOK AT ERRORS IN CHROME **

![CHROME](https://www.rahultrikha.com/content/images/2015/01/Screen_Shot_2013-06-15_at_1-46-51_PM.png)


* The type of error and the error 
message are shown in red In the console .


## **HOW TO LOOK AT ERRORS IN FIREFOX**
![FIREFOX](https://developer.mozilla.org/en-US/docs/Tools/Browser_Console/browser_console_68_02.png)  

Only the JavaScript and 
Logging options need to be 
turned on. The Net, CSS, and 
Security options show other 
information. 


We can typing in the console in firefox and in chrome just type code into the console 
and it will show you a result.


