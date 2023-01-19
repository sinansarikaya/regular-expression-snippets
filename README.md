
# Regular expression snippets

```
.     - Any character except new line
\d    - Digit (0-9)
\D    - Not a digit (0-9)
\w    - Word character (a-z, A-Z, 0-9, _)
\W    - Not a word character
\s    - Whitespace (space, tab, newline)
\S    - Not whitespace (space, tab, newline)
```

```
\b    - Word boundary
\B    - Not a word boundary
ˆ     - Beginning of a string
$     - End of a string
```

```
[]    - Matches characters in brackets
[^ ]  - Matches characters NOT in brackets
|     - Either or
( )   - Group 
```
<br />
Quantifiers:

```
*     - 0 or more
a*    - 0 or more of a
?     - 0 or 1
a?    - 0 or 1 of a
+     - 1 or more
a+    - 1 or more of a
{3}   - Exact number
a{3}  - Exactly 3 of a
a{36} - Between 3 and 6 of a
{3,4} - Range of numbers (minimum, maximum)
a*?   - Lazy quantifier
```



