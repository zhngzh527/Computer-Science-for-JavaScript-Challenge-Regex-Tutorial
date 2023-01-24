# Regex Tutorial for Matching a URL

A regular expression is a pattern that is matched against a subject string from left to right. Regular expressions are used to replace text within a string, validate forms, extract a substring from a string based on a pattern match, and so much more. The term "regular expression" is a mouthful, so you will usually find the term abbreviated to "regex" or "regexp". This tutorial explains how a regex for matching a URL functions, breaking down each component of the expression and describing what it does.

## Summary

This tutorial describes the regex, or sequence of characters that defines the specific search pattern of a URL, ```/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/```. The characters used in this specific search pattern are called metacharacters, which instead of indicating a literal character, indicates a more generalized pattern. Regex are frequently used to validate input, as when included in code or search algorithms, regex can be used to find certain patterns of characters in a string, or find and replace a character or sequence of characters within a string.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)

## Regex Components

Components of a regex matching a URL include:
* Anchors ```^``` ```$```
* Quantifiers ```*``` ```+``` ```?``` ```{}```
* Character classes ```\d``` ```\w``` ```.```
* Grouping and capturing ```()```
* Bracket expressions ```[]```
* Greedy match ```*```

### Anchors

The first type is the caret `^` that checks if the matching character is the first character of the input and the second type is the dollar sign `$` which checks if a matching character is the last character of the input string.

In the URL regex, we see two slashes at the start and end, as seen in ```/wlk/```, which flags, or delimits the beginning and end of a regex pattern. We then see ```^``` and ```$``` at those two ends to signify the search pattern found in between those characters.

### Quantifiers

### Character Classes

### Grouping and Capturing

## Author

Created by Zhongcheng Zhao. For additional questions and information, please go to my [GitHub profile](https://github.com/zhngzh527)
