**3-5C: Own Variables.  Variables declared within an encapsulation, but not within a function, procedure, or process of the encapsulation, shall remain allocated and retain their values throughout the scope in which the encapsulation is instantiated.**

Harlan's encapsulation unit is a class, and this means that classes can contain `val` (immutable) and `var` (mutable) declarations.  Each instance of a class has its own copy of the variables declared by `var`.
