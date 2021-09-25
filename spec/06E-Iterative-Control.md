**6E: Iterative Control.  There shall be an iterative control structure. The iterative control may be exited (without reentry) at an unrestricted number of places. A succession of values from an enumeration type or the integers may be associated with successive iterations and the value for the current iteration accessed as a constant throughout the loop body.**

There are two iterative statements.

Indefinite iteration is done with a `loop...while...repeat` statement.

Definite iteration is done with a `loop for...while...repeat` statement.
The `for` clause consists of a variable, an initial value, and a
reinitialization.  The `while` clause allows a quick escape.
This is done by tail recursion.

Functions can contain definite iteration but not indefinite iteration.

