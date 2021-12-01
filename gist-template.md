# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Matching an Email
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
^ Matches any string contained within the parentheses ()
^ Beginning anchor
$ Ending anchor

### Quantifiers
- {2,6}
Matches a character string with between two to six characters

### OR Operator
- [a-z0-9_\.-]
Matches a character string with characters between a to z or 0 to 9 or _ or . or –

- [\da-z\.-]
Matches a character between a to z

### Character Classes
-\d 
. matches any character
\d matches a single character
\w matches a single word
\s matches a single white space character

### Grouping and Capturing
- ()
The parentheses () captures characters within the parentheses

### Bracket Expressions
- []
Organizes the searches into separate search criteria, can be multiple cases of the same criteria

### Greedy and Lazy Match
- + 
Expand the match through the provided text for a much as possible

## Author
Name: Robert Vanooyen
Github: https://www.github.com/rvanooyen/

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
