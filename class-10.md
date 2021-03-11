# Error handling and debugging
When you are writing JavaScript, do not expect to write it perfectly the first time, Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it too. 
what is debugging ?
Debugging is the process of finding errors that involves a process of deduction. 
# the stack 
the javascript interpreter processes one line of code at a time, when a statement needs data from another function, it stacks the new function on top of the current task.
how does that happen ?
when a statement has to call some other code in order to do its job, this task goes to the top of the pile of things to do, once its been performed the interpeter goes back to the task in hand, with every new item a new excution contect happens.
## types of errors?
JavaScript has 7 different types of errors, Each creates its own error object, which can tell you its line number and gives a description of the error. 
1. RangeError
This is thrown when a number is outside an allowable range of values.

2. ReferenceError
This error is thrown when a reference made to a variable/item is broken. That is the variable/item doesn’t exist.

3. SyntaxError
This is the most common error we encounter. This error occurs when we type code that the JS engine can understand, This error is caught by the JS engine during parsing but There are different stages in the JS engine our code is put through before we see those results on the terminal.

4. TypeError
TypeError is used to indicate an unsuccessful operation when none of the other NativeError objects are an appropriate indication of the failure cause.

5. URIError
This indicates that one of the global URI handling functions was used in a way that is incompatible with its definition.

6. EvalError
This is used to identify errors when using the global eval() function.

7. InternalError
This error occurs internally in the JS engine, especially when it has too much data to handle and the stack grows way over its critical limit.

how can we detect these errors?
The console helps narrow down the area in which the error is located, so you can try to find the exact error, or if you know that you may get an error, you can handle it gracefully using the try, catch, finally statements Use them to give your users helpful feedback. 