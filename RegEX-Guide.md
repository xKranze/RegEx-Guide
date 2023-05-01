# RegEx Guide

This will be a RegEx guide for me and anyone else that would like to see notes and description of about RegEx.

## Summary

  What is a RegEx? A regex, which is short for regular expression, is a sequence of characters that forms a pattern. When included in code or search regex can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also used alot to validate inputs.

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
<hr>

### Anchors

-Characters such as "^" and "$" are considred to be anchors. Anchors are speciial characters used to match a specific position in the string/text.

`^` (Caret) The Caret anchor always asserts that the current position in a string is the beginning.

`$` (Dollar Sign) The Dollar sign is the opposite of the Caret mentioned above.  This represents the ending of a string/text.

Here is an example of the hexidecimal color code displaying the use of the anchors as you can see here the Caret is being used in the beginning and dollar sign at the end. `^#([A-Fa-f0-9]{6}|[A-Fa-f0-9]{3})$`
<hr>

### Quantifiers

-Quantifiers are special characters that are used to speicify the number of times a specific character should be matched.  This allows you to specify how many times an element must appear in a string for a match to be found.

The most simple quantifier are numbers contained in curly braces `{n}`
For example `/\d{4}/` will search for any string that contains a year for example "2023", "1234".

`\d` Will match a digit number ranging from 0-9

`{4}` is the quantifer saying we want `\d` to should appear 4 times
<hr>

### OR Operator
-The OR operator will alow you to match with one expression OR the other.  For example using the bar symbol `|` to find numbers 1 or 2 or 3 or 4 string below.

`/^(1|2|3|4)$/`
<hr>


### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author


Hi Im Jimmy Yin and im in the 5th month of coding bootcamp, started bootcamp with absolutely no coding experience and have came a long way from where i started.  Im eager to learn all i can on my journey to become a full stack developer! Here is a link to my git hub account.

-GitHub: <a href="https://github.com/xKranze">Jimmy Yin</a>
