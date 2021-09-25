**4F: Operator Precedence Levels.  The precedence levels (i.e., binding strengths) of all (prefix and infix) operators shall be specified in the language definition, shall not be alterable by the user, shall be few in number, and shall not depend on the types of the operands.**

In Harlan we extend this by allowing the compiler
to deduce from the operator whether the operation is:

 * commutative or not
 * left associative, right associative, or not associative
 
To add a method to an operator, make sure that its name
is prefixed by the reserved word `operator`
(thus `operator +`, not just `+`),
and that its arguments are named `left:` and `right:`,
or just `right:` if it is unary.
 
Here is a list of operators from highest to lowest priority:



