**2G: Numeric Literals.  There shall be built-in decimal literals. There shall be no implicit truncation or rounding of integer and fixed point literals.**

An integer literal is a string of digits.
Note that literals do not contain minus signs:
`-32` is the application of the `-` operator to the literal `32`.

A double-precision float literal is a string of digits with up to one decimal point.
The decimal point may not appear at the beginning or the end of the literal.
After the digits, the character `E` or `e` may be present; if so,
it is followed by an optional sign `+` or `-` and another string of digits.

A single-precision float literal has the same format as a double-precision
literal, but uses `D` or `d` rather than `E` or `e`.
