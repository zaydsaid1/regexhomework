# Regex Tutorial

In this tutorial, you will be able to get a breakdown of what Regex does, and how it fits in to computer science, and coding. In the example provided, you will see what each character means, and how it fits in to your code.

## Summary

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
Regex (short for regular expression) is defined as a series of special characters that define a search pattern used by developers. Regex is read from left, to right. In the above code, these characters are allowed to be in a users’ email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

### Anchors

^ and $ are anchors in Regex. ^ is to be put in the beginning, while $ is put at the end.

### Quantifiers

Quantifiers are a set of characters that limit the strings of the email. In this example, + and {} would be quantifiers. If a user sees a +, it means that the pattern can be matched one or more times. For curly brackets, there are multiple definitions depending on how many characters are seen in the curly brackets. Using this example, users will see {2,6}. These numbers mean that the email has to have more than 3 numbers, and have less than 6 numbers.

### Character Classes

There are two types of character classes: character escapes, and character classes. A character escape uses a backslash to make the characters located in a square bracket invalid. It’s used as a literal interpretation. In this example, an escape can be seen as a backslash. A character class is any of the characters that are found in the regex sequence.

### Grouping and Capturing

The most common way to describe parenthesis in Regex is a subexpression. This means that the characters can be read easier by being broken up in to sections. In this example, we see three sets of parentheses. Each of these sections are separate parts of the email itself.

### Bracket Expressions

If you look closely at the characters, there are 3 sets of brackets. These brackets are to designate the character set. Any character that is located in a bracket set are included in the email. Examples include [a-z], and [0-9]. In this example, each brackets represents a part of the email.

### References

https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial

## Author

Zayd Said
GitHub:https://github.com/zaydsaid1/regexhomework

Link to GIST:https://gist.github.com/zaydsaid1/dfbd4eff38260cea3e2901821c6203fb