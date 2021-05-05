# Error Handling & Debugging

JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

## Order Of Excution

To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:
 
 ## Excution contexts

 The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

 ## execution context and hoisting 

 Each time a script enters a new execution context, there are two phases
of activity: 1.prepar

* The new scope is created
* Variables, functions, and arguments are create 
* The value of the this keyword is determined

            2.execute:
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements


## understandig Scope

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

## understandigh errors

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

## error objects

* Error: Generic error - the other errors
are all based upon this error
* Syntax Error: Syntax has not been followed
* Ref erenceError:Tried to reference a variable that is
not declared/within scope
* TypeError: An unexpected data type that
cannot be coerced
* Range Error: Numbers not in acceptable range
* URI Error: encodeURI ().decodeURI(),and
similar methods used incorrectly
* Eval Error: eva l () function used incorrectly

