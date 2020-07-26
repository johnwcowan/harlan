**5C: Scope of Declarations.  Everything (including operators) declared in a program shall have a scope (i.e., a portion of the program in which it can be referenced). Scopes shall be determinable during translation. Scopes may be nested (i.e., lexically embedded). A declaration may be made in any scope. Anything other than a variable shall be accessable within any nested scope of its definition.**

The scope of a variable defined within a class or a procedure
is from the declaration to the end of the class or procedure.
The scope of an encapsulated procedure is the class encapsulating it.
The scope of a global procedure is the whole program.
