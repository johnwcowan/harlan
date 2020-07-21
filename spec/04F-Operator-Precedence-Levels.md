**4F: Operator Precedence Levels.  The precedence levels (i.e., binding strengths) of all (prefix and infix) operators shall be specified in the language definition, shall not be alterable by the user, shall be few in number, and shall not depend on the types of the operands.**

In Harlan we extend this by allowing the compiler
to deduce from the operator whether the operation is:

 * commutative or not
 * left associative, right associative, or not associative
 * unary or binary (`-` is a special case, as it is both)
 
Here is a list of operators from highest to lowest priority:

