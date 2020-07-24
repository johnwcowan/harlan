**4C: Side Effects.  The language shall attempt to minimize side effects in expressions, but shall not prohibit all side effects. A side effect shall not be allowed if it would alter the value of a variable that can be accessed at the point of the expression. Side effects shall be limited to own variables of encapsulations. The language shall permit side effects that are necessary to instrument functions and to do storage management within functions. The order of side effects within an expression shall not be guaranteed. [Note that the latter implies that any program that depends on the order of side effects is erroneous.]**

What this amounts to is that a function
consists of declarations and restricted
kinds of statements followed by a single expression
whose value is returned as the function's value.

(It should be possible to loop within a function
with constraints of some sort;
I don't know just what yet.
Probably this amounts to syntactic sugar for
tail recursion.)

A function can throw an exception.
It can also catch an exception,
but it has no access to details about the object thrown.

When a class variable is assigned within a function,
its value can only depend on constants and other class variables.

Functions can depend on immutable variables
and their own arguments and local variables.
An encapsulated function also have access
to mutable variables declared in the same class.
