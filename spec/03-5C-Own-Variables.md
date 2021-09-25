**3-5C: Own Variables.  Variables declared within an encapsulation, but not within a function, procedure, or process of the encapsulation, shall remain allocated and retain their values throughout the scope in which the encapsulation is instantiated.**

Harlan's encapsulation unit is a class, and this means that classes can contain `class var` declarations for variables that are mutable with one copy per class.  There are also `val` (immutable), `var` (mutable with one copy per instance), `func`, and `sub` declarations in classes.
