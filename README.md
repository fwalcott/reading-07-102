# Read 07

## What is a Script, and How Does it Work.

A script is a series of instructions like a recipe. It tells the computer what to do by giving it step by step instructions. The browser may not use all of it, and run different code sections depending on user interactions with the page.  When you are writing a script, start with the big picture of what you want to do. Then break it down into smaller steps a computer can understand. First, you define the goal. Second, you set the script, and last, you have to code each step. 
You have to give a computer a series of detailed instructions. Using vocabulary(words computers understand) and syntax (how you put them together to make instructions a computer can follow). 

## What is a Function, and How Do You Call One? 

A function lets you group a series of statements to perform a task.  You can reuse a function anywhere in your script, so you don't have to repeat yourself. 

***Here is an example of a simple function: 
~~~

function sayHello() { 
document.write ('Hello') 
} 
~~~
***I can write sayHello anywhere in my script, and this function will run. 

*Remember, a function will not run unless it's called.   

**1.) A function can store instructions for a specific task.   
**2.) You call a function when you need to perform that task 
**3.) The function executes the code in the code block (inside the {}) 
**4.) When the function is finished the code will continue to run from the point it was initially run 

## What is an Expression? 

An expression relies on operators to create a single value from multiple ones.  They are two types. 
~~~
*Assign a value to a variable: 
var color = 'orange'; 

*Use two or more values to return a single value. 
var area = 3*2
area = 6  
~~~

**They are five operators**  
1.Assignment
color = 'orange'; 
2.Arithmetic (performs basic math)  
area = 3*2 ;
3.String   
greeating = 'Hello' + ''+'World!';
4.Comparison 
buy = 1<5; 
5.Logical 
buy = (1<5) &&(2>4);

The arithmetic operators are all things we have seen before addition(+), subtractions(-), division(/), and multiplication(*).  *But the are a few others that aren't as recognizable.*  ***Increment (++) adds one to the current number. Decrement (--) subtract one from the current number. Modulus (%) divides a number and returns a remainder (10%3) will return 1.*** 
