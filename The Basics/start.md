# Start
First of all, welcome to computer science! Whether you're planning to make something as advanced as an AI in python, or something as simple as a discord bot, computer science skills are necessary to progress.
As a start, let's try running this file with this specific code in it.
(if you don't have the necessary resources for this step, such as not having IDLE or VS Code, you can check their respective guides)
```py
x = "Hello World!"
print(x)
```
When you run this code, it should result in 
```
Hello World
```
appearing in your terminal. You might be wondering right now, "How does this work, and why does it work in the first place????".
By the end of this guide, you should be able to easily comprehend this type of code, along with more advanced and harder to read types of code in the future.
Now, let's dissect this code to see what it actually does!

# Dissection

### Variable Assignment
First, in this piece of code, we see a variable assignment, denoted by the "=" sign.
```py
x = "Hello World!"
```
In general computer science, variables are like "names" for data, that you can use (almost) whenever you want.
However, there's a difference between a name and a value. For example, let's look at this:
```py
x = 123
y = x
print(y)
```
You might think there's 2 copies of the number `123`, one in `x` and one in `y`. However, Python doesn't copy data between variables, so `y` is just "referring" to the value at `x`. (Remember this, we'll cover this in more detail later)
Variables can be reassigned in Python, meaning while Python is running this program line by line (called an "interpreter", we'll get into more detail down below), the value of `x` can change.
```py
x = 123
y = x
print(x,y)
x = 13
y = x
print(x,y)
```
There's so many variable assignments! What do you think this program will print out? Let's see what it actually does print out!
```
123 123
13 13
```
Woah, this is crazy! "How does this happen?" I hear you think. Well, this has something to do about Python being an "interpreted" language. In computer science, an interpreter is defined as a program that runs source code (the code you have in the file you're running) line by line. Since Python is interpreted, it starts executing code from top to bottom (in some cases, not exactly, see [control flow](control_flow.md) for more detail). To demonstrate this in the context of our program here, let's see what happens to `x` and `y` throughout our execution.
```
x = 123
```
As we learned earlier, this line just assigns a value to the name/variable `x`.
```
y = x
```
As we also learned earlier, the name y is created and just "refers" to `x`'s value.
```
print(x, y)
```
This is a special line, that contains a thing called a "function". You don't need to know quite what it is until later, so let's say that this takes your values supplied to it and puts it into the terminal.
```
x = 13
```
`x` is reassigned to the value of `13`.
```
y = x
```
`y` is reassigned to refer to the *new* value of `x`, `13`.
```
print(x, y)
```
This puts the values supplied to it and puts it into the terminal.
Now that we've covered the basics of variables, and somewhat covered what that obscure `print` statement does, let's move on to [operators](operators.md)!
