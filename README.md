# Matching A Hex Value
This ia a walkthrough of a regular expression (REGEX) for mathcing a hex value. In this walkthrough you will find a short tutorial on the individual components of the regex, as well as how to use it in its entirety

## Summary

To match a hex value, we are going to be using the following expression:

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

This expression is broken down into anchors, quantifiers, OR operator, character classes, grouping and capturing, bracket expressions, and greedy and lazy match expressions.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors match to a position either before or after character(s)
- `^` represents the beginning of the text.
- `$` represents the end of the text.

### Quantifiers
Quantifiers match the number of instances of a character class, group, or character within a string.
- `{n}` represents the number of characters or character classes we want to match.
- `?` is a quantifier that matches the preceding item character either zero or one times.

### OR Operator
The OR operator is a term that represents alternation in a regex.
- `|` is known as an OR Operator
  * Ex: `green|orange` allows for either green OR orange within the string.
-  Our expression contains `[a-f0-9]{6}|[a-f0-9]{3}`. So, we are looking for either `[a-f0-9]{6}` or `[a-f0-9]{3}

### Character Classes
Character classes define certain characters, meaning you can distinguish the difference in letters and digits. You can use a hyphen to define a specific range of characters.

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
