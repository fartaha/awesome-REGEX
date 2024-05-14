# awesome-REGEX
Awesome regular expression (REGEX) commands anyone must know:

1. **Exact Match**: The most basic form of regex involves matching a sequence of characters. For instance, if you want to match 'Hello World', you can simply use `Hello World` as your regex.

2. **Any Character (.)**: The dot `.` matches any character except a newline character. For example, `a.b` can match 'acb', 'a2b', 'a$b', etc.

3. **Zero or More (*)**: The asterisk `*` matches zero or more instances of the preceding character. For example, `a*` can match '', 'a', 'aa', 'aaa', etc.

4. **One or More (+)**: The plus `+` matches one or more occurrences of the preceding character. For example, `a+` can match 'a', 'aa', 'aaa', etc., but not an empty string.

5. **Zero or One (?)**: The question mark `?` matches zero or one occurrence of the preceding character. For example, `a?` can match '' or 'a'.

6. **Character Set ([])**: Square brackets `[]` define a character class, matching any character within the brackets. For example, `[abc]` can match 'a', 'b', or 'c'.

7. **Ranges (-)**: You can specify a range of characters using `-` inside a character set. For example, `[a-z]` matches any lowercase letter, and `[0-9]` matches any digit.

8. **Negation (^)**: The caret `^` at the start of a character set negates the set, matching any character not in the set. For example, `[^0-9]` matches any non-digit character.

9. **Groups and Capturing (() and $1, $2, etc.)**: Parentheses `()` are used to create a group, which can be referenced in the replace pattern. For example, `(abc)` creates a group matching the string 'abc', and `$1` in the replace pattern refers to this group.

10. **Alternation (|)**: The pipe `|` acts like a boolean OR, matching the pattern before or the pattern after it. For example, `abc|def` matches 'abc' or 'def'.
