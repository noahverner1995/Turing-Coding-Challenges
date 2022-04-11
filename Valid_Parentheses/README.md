## Valid Parentheses:

Given a string `s` containing just the characters `'('`, `')'`, `'['`, `']'`, `'{'`, `'}'`, determine if the input string is valid.

An input string is valid if:

- Open brackets must be closed by the same type of brackets
- Open brackets must be closed in the correct order

## Constraints

- `1 <= s.lenght <= 104`
- `s` consists of parentheses only `'()[]{}'`

Example 1:

`Input: s = "()"`

`Output: valid`

Example 2:

`Input: s = "()[]{}"`

`Output: valid`

Example 3:

`Input: s = "(]"`

`Output: invalid`

Example 4:

`Input: s = "([)]"`

`Output: invalid`

Example 5:

`Input: s = "{[]}"`

`Output: valid`
