**5B: Declarations of Variables.  Each variable must be declared explicitly. Variables may be of any type. The type of each variable must be specified as part of its declaration and must be determinable during translation. [Note, 'variable' throughout this document refers not only to simple variables but also to composite variables and to components of arrays and records.]**

Variables can be declared with `var` and `class var` declarations.
Types do not have to be specified, as they can be inferred
from their initial values.
However, a type must be given when the type of a variable is a supertype
of the type of its initial value.
