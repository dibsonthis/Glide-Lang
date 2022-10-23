# Glide
Documentation for the Glide programming language.

## Preface

The name 'Glide' (previously 'Flow') is not set and can change at any time. The programming language in this documentation will be referenced as Glide for the time being.

## Purpose

The purpose of Glide is simple. I wanted a way to easily read and write data transformation workflows. With this in mind, the language relies heavily on the arrow (injection) operator '->' to feed data long the chain. This documentation will feature examples of how it's used.

The other reason this language exists, is learning. I wanted to learn how languages are made and uncover the black magic of parsers/iterpreters/compilers. Glide is my 15th attempt at a new language, the ones before have been abandoned due to the codebase being an absolute mess, or the language itself offering nothing new and exciting (at least for me). I decided to stick it out with Glide, and hoping to end the cycle of project hopping by continuing to refactor and upgrade instead of delete and retry.

# Syntax

## Data types

Glide only has a few simple data types: bool, int, float, string, list, object and empty

The language is dynamically typed and therefore there is no need to declare the variable type. (Note: a type system is in the works, and once fully implemented, this documentation will be updated accordingly. I'm still unsure whether I want typing to be a requirement by the compiler, or a choice given to the programmer. Stay tuned, I guess).

Example - Variable declaration:

```
x = 12
y = 3.45
str = "hi there, universe"
ls = [ 1 2 3 "four" 5.0 ]
obj = @{
  name: "John"
  age: 45
}
```
