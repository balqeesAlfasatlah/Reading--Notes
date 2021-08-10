# Functional programming

## 1. What is functional programming?
is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## 2. What is a pure function and how do we know if something is a pure function?

It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects

## 3. What are the benefits of a pure function?
The code’s definitely easier to test. We don’t need to mock anything

## 4. What is immutability?

When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## 5. What is Referential transparency?
If a function consistently yields the same result for the same input, it is referentially transparent.
---

## 6. What is a module?
set of related functions and components semantically related with its own functional responsibility.

## 7. What does the word ‘require’ do?
intended to add separate pieces of code (“modules”) to the current scope

## 8. How do we bring another module into the file the we are working in?
using 'require'

## 9. What do we have to do to make a module available?
exports