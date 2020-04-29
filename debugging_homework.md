# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?
A break point allows the code to run till the breakpoint tells it to pause so we can debug up to that point
2. Does the line of code on a breakpoint run when you start debugging?
No it'll run up to the line before and then it'll pause the application and start debugging
3. How do we debug the next line of code?
To debug the next line of code we use the step over button in the debugger console
4. What does the step into command do?
Step Into moves into the appropriate class where the method in the breakpoint line was created
5. What is the difference between evaluate expression and evaluate code fragment?
Evaluate expression allows us to run a java method seperately from the rest of the code, it does not need semi-colons
Evaluate code fragment allows us to run multiple lines of code and store things in variables, it does need semi colons 
