**4B: Type of Expressions.  It shall be possible to specify the type of any expression explicitly. The use of such specifications shall be required only where the type of the expression cannot be uniquely determined during translation from the context of its use (as might be the case with a literal).**

Explicit typing of an expression is done with `the` <type> <expression>.  It is a compile-time error if the inferred type doesn't match the explicit type.
