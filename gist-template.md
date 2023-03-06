# Regex: Matching an Email
This is a Regex tutorial for matching an email using this expression `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`. We use this when validating emails using Node or MongoDB.

## Summary
Regular expressions are a pattern that attempts to match input text. They consist of character literals, operators, or constructs.

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
`^` is used for matching an email and indicates the beginning of the string.
`$` is used to indicate the end of the string.
`(m)`, is not enabled so the regex will end at `$`.

### Quantifiers
`+` operator, which will connect the users email name + email service + `.com`.
`{2,6}`, which will allow a match range of 2-6 characters for the character set of `[a-z\.]`.

### Grouping Constructs
Group #1 is `([a-z0-9_\.-]+)` that matches the user email name.
Group #2 is `([\da-z\.-]+)` which matches email service.
Capture group #3 is `([a-z\.]{2,6})` for the `.com`.

### Bracket Expressions
Bracket expressions for email validation  `[a-z0-9_\.-]`, matches any letter a-z and is case sensitive. It also matches 0-9 and the characters "_" , "-" , and ".".

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

My name is Beau Ben-Rhouma and I'm a student of the U C Berkeley Coding Boot Camp.

Beau Ben-Rhouma | Github: [BRhouma](https://github.com/BRhouma)
