**10D: Exception Handling.  There shall be a control structure for discriminating among the exceptions that can occur in a specified statement sequence. The user may supply a single control path for all exceptions not otherwise mentioned in such a discrimination. It shall be possible to raise the exception that selected the current handler when exiting the handler.**

In a subroutine, the syntax is
a `try...except...else...finally` statement.

Inside a function, the syntax `catch <expr1> else `expr2`
evaluates <expr1> and returns its value,
unless an exception is raised,
in which case `expr2` is evaluated and is value returned.

Exception semantics is terminating.

The `raise` <expr> raises an exception.
The value of <expr> can have any type.
