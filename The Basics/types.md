# Python's built-in types
> ### What is a type!?!?!?!
> Types are a central part of almost every programming language today, part of a programming *paradigm* called OOP. (we'll talk more about this soon)
> A data type (which is what we're gonna cover) is a collection or a group of values that can be manipulated or changed using *functions* or *operators* (for operators, it's a lot more complicated, we'll cover that a LOT later)

Now that we know what a type is, let's get into what types python already defines for you!

### `str` - strings
Strings, which are what we call a collection of characters/text in computer science, are one of the most common types you're probably going to use in Python. Strings are pretty self explanatory, and they support these operations:
```+``` (yeah, not quite a lot)
The only reason why Python supports this strange addition operator for strings is for string *concatenation*. Concatenation, which may sound like an intimidating word, really means *putting together*. For example, let's take this as a variable `x`:
```py

x = "abc" + "xyz"
print("x")

>> "abcxyz"
```
Woah! That's cool, right? Strings also support formatting/inserting variables as if they were part of the string. There are 2 ways to format variables into strings.
***f-strings***
This is the more elegant way of inserting variables. Using this format, you can just enter a variable name into a string, and it works (well, not quite, but we'll cover that a LOT later.)
You can insert variables into a f-string using this format: `f"hey, {x}!"`. This would display ```hey, abcxyz!``` if it was put through `print()`.
The curly braces syntax (basically "rules" on how a specific language or, in this case, f-strings, work) for f-strings has a lot more flexibility though, which you can see [here](https://fstring.help/cheat/).