**7C: Scope Rules.  A reference to an identifier that is not declared in the most local scope shall refer to a program element that is lexically global, rather than to one that is global through the dynamic calling structure.**

If an identifier is not declared in the innermost scope,
it is searched for in the next innermost scope,
and so on until the global scope is reached.

It's an open question whether shadowing is allowed.
