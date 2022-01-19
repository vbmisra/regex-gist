# Regex Gist (Tutorial)

This tutorial will explore how regex (short for: regular expressions) work and what they are.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

The goal of this tutorial is to allow the reader to have a quick-reference guide to the basics of regex (also known as regexp). Regex is a sequence of characters that specifies a search pattern in text, thereby allowing users to create search patterns that match and locate text. As a result, regex are commonly used in search engines and find/replace dialogs of word processors.

Here is an example of regex code. It says "Hello World":

(?<=\/)\w+

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
In regex, anchors are used to pin the match at a specific position. Anchors can match a position before, after, or between characters. The table below specifies common anchors and their functions.

| Anchor   | Example  | Description                                  |
|  :--:    |   :--:   | :-----:                                      |
|   ^      | ^start   | matches any string that starts with "start"  |
|   $      | end$     | matches any string that ends with "end"      |
| ^ $      | ^middle$ | exact match to word "middle"                 |

### Quantifiers
Quantifiers in regex specify how many times a specific character, group or character class must occur in the input to find a match. Below is a table that specifies quantifiers and their functions.

| Quantifier | Example  | Description                                          |
| :-----:    | :--:     | :----:                                               |
| *          | c*       | matches preceding item "c" 0 or more times           |
| +          | c+       | matches preceding item "c" 1 or more times           |
| ?          | c?       | matches preceding item "c" 0 or 1 time               |
| {}         | c{n}     | n is a positive integer; matches n occurrences of "c"|
| {,}        | c{n,m}   | match "c" from n to m times                          |
| {,}        | c{n,}    | match "c" at least n times                           |


Note: quantifiers may be sub-categorized as "lazy" or "greedy." "Lazy" implies the quantifier will consume as little as possible, meaning it will match the shortest possible string. "Greedy" means the opposite - the quantifier will consume as much as possible, meaning it will match the longest possible strings. Adding a "?" quantifier to the end of another quantifier can convert from "greedy" to "lazy," i.e. c{n} is greedy but c{n}? is considered lazy. 

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

Varoun Misra is an aspiring full-stack developer / software engineer. Feel free to check out more of his work via GitHub at:

https://github.com/vbmisra
