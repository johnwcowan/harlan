**4C: Side Effects.  The language shall attempt to minimize side effects in expressions, but shall not prohibit all side effects. A side effect shall not be allowed if it would alter the value of a variable that can be accessed at the point of the expression. Side effects shall be limited to own variables of encapsulations. The language shall permit side effects that are necessary to instrument functions and to do storage management within functions. The order of side effects within an expression shall not be guaranteed. [Note that the latter implies that any program that depends on the order of side effects is erroneous.]**

Functions have access to immutable variables
and local arguments and local variables.
An encapsulated function also have access
to mutable variables declared in the same class.

A function body contains `val` and `var` declarations
and a limited set of statements,
of which the last is `return` followed by an expression.
