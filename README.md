# Computer-Science-Regex

This challenge is to explain and walk through about <b> "Regular Expression" </b> 

## Summary

What Is a Regex?
A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
- Matching Fixed Strings.
- Matching Special Characters.
- Matching Character Sets.
- Specifying Groups and Fields.
- Evaluating Occurrences.
- Specifying Location.
- Specifying Alternatives.
### Anchors
Anchors have special meaning in regular expressions. They do not match any character. Instead, they match a position before or after characters:
 ^ – The caret anchor matches the beginning of the text.
 $ – The dollar anchor matches the end of the text.
 Example:
    let str = 'JavaScript';
    console.log(/^J/.test(str));

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.
/\w*/.test('abc123') // true
/\w*/.test('') // true. * = 0 to many

### OR Operator
The pipe character | is the selection operator. It matches alternatives. Suppose a pattern should match the strings 1 and 2

### Character Classes
Character Class | Character Set, you can tell the regex engine to match only one out of several characters. Simply place the characters you want to match between square brackets []. 
### Flags
It is optional parameter to a regex that modifies its behavior of searching, there are 6 flags i g s m y u.

### Grouping and Capturing

### Bracket Expressions
Bracket Expressions, these are special kind of character classes.
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
Matches any character in the square brackets.

### Greedy and Lazy Match
We should understand how the search works very well if we plan to look for something more complex.
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/
Greedy matches an element as n number of times.
And lazy matches an element as few times.

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author
My Name is -->
* [Vinay Vallabhaneni](https://github.com/vinssm)

Here is my github repo: https://github.com/vinssm

## Resources:
* [Google](https://www.google.com/)


