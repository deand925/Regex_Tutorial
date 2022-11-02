# Regex Tutorial

Regex or regular expressions search for a sequence of characters that is search based based on a specific patterns of text. This tutorial will show regex works and give an example.

## Summary

Matching a Hex Value

During this tutorial I will be explaining how to match an Hex Values using regex or regular expressions. The regex used will be set up to match different variations of hex formats. The two formats are Hex Triplet Format and Shorthand Hex Format.

Regular Expression used

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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

<mark>/^</mark>#?([a-f0-9]{6}|[a-f0-9]{3})<mark>$/</mark>

In this example the anchors /^ and $/ are highlighted. They are being used to represent the start and ending of our expression. 


### Quantifiers

/^#<mark>?</mark>([a-f0-9]<mark>{6}</mark>|[a-f0-9]<mark>{3}</mark>)$/

In this example the quantifiers used are "?,{}". The quantifiers are highlighted in the expression above. They are used to communicate how many characters are expected in the input for a match to be found. Quantifiers specifiy how many times a character, group or character class must be present in the input. 


### OR Operator

/^#?([a-f0-9]{6}<mark>|</mark>[a-f0-9]{3})$/

In this example the "or" operator is highlighted above. The "or" operator is used with the | element. As we previously discused there are two different types of hex formats (Hex Triplet Format and Shorthand Hex Format). Both of these formats need to be taken into consideration when the expression. By using the "or" operator we are seperating the two character classes so that the hex value could be either 6 or 3 characters in length.

This shows how the "or" operator breaks down both options. As you can see the "or" operator or | seperates the two character classes. 

/^#?(<mark>[a-f0-9]{6}</mark>|<mark>[a-f0-9]{3}</mark>)$/


### Character Classes

/^#?(<mark>[a-f0-9]</mark>{6}|<mark>[a-f0-9]</mark>{3})$/



### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
