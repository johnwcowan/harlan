**2D: Other Syntactic Issues.  Multiple occurrences of a language defined symbol appearing in the same context shall not have essentially different meanings. Lexical units (i.e., identifiers, reserved words, single and multicharacter symbols, numeric and string literals, and comments) may not cross line boundaries of a source program. All key word forms that contain declarations or statements shall be bracketed (i.e., shall have a closing as well as an opening key word). Programs may not contain unmatched brackets of any kind.**

In order to allow very long string literals,
the compiler is required to treat the application of the `++` operator
to string literals as if they constituted a single string literal.
Thus there is no difference between `"abc" ++ "def"` and `"abcdef"`.
