# RegEx Guide

  In this guide i will be breaking down the Hex Value `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

## Summary

What is a RegEx? A regex, which is short for regular expression, is a sequence of characters that forms patterns. We can use regex in our code or search to match certain patterns given specific parameters we set. These are also often used to validate inputs.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components
<hr>

### Anchors

-Characters such as "^" and "$" are considred to be anchors. Anchors are speciial characters used to match a specific position in the string/text.

`^` (Caret) The Caret anchor always asserts that the current position in a string is the beginning.

`$` (Dollar Sign) The Dollar sign is the opposite of the Caret mentioned above.  This represents the ending of a string/text.

Here is an example of the hexidecimal color code displaying the use of the anchors as you can see here the Caret is being used in the beginning and dollar sign at the end.
`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`
<hr>

### Quantifiers

-Quantifiers are special characters that are used to speicify the number of times a specific character should be matched.  This allows you to specify how many times an element must appear in a string for a match to be found.

In this example `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` there are two types of quantifiers used, one of them is used twice.  The first quantifier used here is the `?` (question mark).  The `?` indicates that the preceding character can occur zero or one times

The second type of quantifier being used represented by the {n} curly braces which contains a numeric value.  In this case `[a-f0-9]{3}` the quantifier `{3}`is used here showing is looking to match a sequence of three characters that can be any letter from a to f, any number from 0 to 9.
<hr>

### OR Operator

The the OR operator allows you to match one or more different expressions.  In this hex example `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` the ones used here are the bar `|` symbol which seperates the two expressions and depending on the parameters needed to match it will match one or the oother expression on other side of the bar.  The other OR operator seen is the brackets `[]` which will match either `[a-f0-9]{6}` OR `[a-f0-9]{3}`.
<hr>

### Character Classes

A character class defines a set of characters and is similar to bracket expressions.  Using our hex regex `[a-f0-9` this will match any lowercase letter from a through f and a number from 0 through 9.
<hr>

### Grouping and Capturing

As some regex gets more complex, you will want to use grouping and capturing to specify part of a string to see if they meet certain parameters.  To do this we use `()` parentheses to group an expression like this `([a-f0-9]{6}|[a-f0-9]{3})` each section within the parenteses is known as a subexpression.
<hr>

### Bracket Expressions

Bracket expressions are basically anything inside the `[]` square brackets.  In our example `[a-f0-9]` in this square bracket we are looking to match a letter from a to f, any number from 0 to 9.
<hr>

## Author


Hi Im Jimmy Yin and im in the 5th month of coding bootcamp, started bootcamp with absolutely no coding experience and have came a long way from where i started.  Im eager to learn all i can on my journey to become a full stack developer! Here is a link to my git hub account.

-GitHub: <a href="https://github.com/xKranze">Jimmy Yin</a>
