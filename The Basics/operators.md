# Python's Operators
Remember when we covered the "=" sign being an *assignment operator*?
Well, Python has way more than just the "=" operator!
### What is an operator?
An operator in computer science definition, is a symbol or series of symbols (e.g =, !=, >=) , OR a word, that change, do something, or compare 2 values to a specific value.
For example, let's take the name `x`, and use the `=` operator to assign it to a value:
```py
x = 123
```
This *changes* the name x such that it refers to the value of `123`.
Let's move on to covering Python's operators now.

### Arithmetical Operators
```
*, **, /, //, +, -, % 
```
All these operators cover basic equations that a programmer may need in their day to day programming use.
Let's explain what all these operators even do:
- `*` - The symbol used for multiplying between 2 values. Example usage: `x = 5*3`, Output: `x = 15`
- `**` - The symbol used to represent exponent values, the left value being the base, the right being the power. Example usage: `x = 3**3`, Output: `x = 27`
- `/` - The symbol used for dividing between 2 values. Example usage: `x = 2/5`, Output: `x = 0.4`
- `//` - The symbol used for floor division, basically division but with remainders included. Example usage: `x = 101/4`, Output: `x = 26`
- `+` - The symbol used for adding between 2 values. Pretty self explanatory usage.
- `-` - The symbol used for subtracting between 2 values. Also pretty self explanatory.
- `%` - Called the modulo operator, this operator returns ONLY the remainder of a division statement. This operator takes the dividend on the right, the divisor on the left. Example usage: `x = 35 % 6`, Output: `x = 1`

### Comparison Operators
```
!=, ==, >, <, <=, >=
```
These operators are probably the most common ones you'll spot in a codebase, due to their important usages. These operators are special, in the way that they ONLY return booleans. (`True`, `False`, we'll go into more detail about built in types later)
Let's explain what these operators do!
- `!=` - The symbol used to denote that something should NOT be the same as another thing.
- `==` - The symbol used to denote that the things being compared should be the same.
- `>` - (cannot be used with non integer/float types, more about this later) The symbol used to denote that some number is greater than another number.
- `<` - (also cannot be used with non integer/float types) The symbol used to denote that some number is less than another number.
- `<=` - (cannot be used with non integer/float types) The symbol used to denote that some number is less than or equal to another number.
- `>=` - (cannot be used with non integer/float types) The symbol used to denote that some number is more than or equal to another number.

### Bitwise Operators
```
&, |, >>, ^ , <<, ~ 
```
These operators are more niche, not used commonly in most codebases. These operators perform binary operations on binary values. This will require more knowledge in Python's built in types, which we'll cover in [types](types.md) (wow, so conveniently placed right after operators!)
