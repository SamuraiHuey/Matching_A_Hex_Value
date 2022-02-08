# Matching A Hex Value
This ia a walkthrough of a regular expression (REGEX) for mathcing a hex value. In this walkthrough you will find a short tutorial on the individual components of the regex, as well as how to use it in its entirety

## Summary

To match a hex value, we are going to be using the following expression:

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

This expression is broken down into anchors, quantifiers, OR operator, character classes, grouping and capturing, bracket expressions, and greedy and lazy match expressions.
