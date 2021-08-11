
# Java Script Call stack

## 1. What is a ‘call’?

data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

## 2. How many ‘calls’ can happen at once?
one

## 3. What does LIFO mean?

When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## 4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
![](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)

## 4. What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

---

# JavaScript error messages && debugging

1. What is a ‘refrence error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

2. What is a ‘syntax error’?

I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

4. What is a ‘tyep error’?

Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5. What is a breakpoint?

breakpoints it is easier to create a code execution in scenarios like this by taking into account the call stack which is available, for example, in chrome developer tools “sources” tab.

6. What does the word ‘debugger’ do in your code?

the easiest and maybe the most common way its to simply console.log() the variables you want to check or, by using chrome developer tools,