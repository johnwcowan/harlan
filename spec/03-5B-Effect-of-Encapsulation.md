**3-5B: Effect of Encapsulation.  An encapsulation may be used to inhibit external access to implementation properties of the definition. In particular, it shall be possible to prevent external reference to any declaration within the encapsulation including automatically defined operations such as type conversions and equality. Definitions that are made within an encapsulation and are externally accessible may be renamed before use outside the encapsulation.**

Encapsulations are called classes.
A class has a hierarchical name solely for organization;
classes in the same part of the hierarchy have no necessary
relationship to each other.  All classes are publicly visible.

A class can *extend*, *incorporate*, or *import* other classes.
More than one such relationship may subsist between two classes.
Classes can contain methods (either procedures or functions),
constants, and variables.  Each such entity can be
*public*, *joint*, or *private*.

 * When class A extends class B, then the public methods of
   B must be overridden by public methods of class A,
   and an A can be used where a B is expected,
   but the two classes do not share code as a result of extension.
   
 * When class C incorporates class D, then the non-private
   methods of each class are visible in the other as joint methods.  
   Incorporation is transitive and loops are permitted,
   so that a group of incorporating and incorporated methods
   share a single namespace of non-private methods.
   Any class has the ability to hide or rename the methods
   of other classes in the group either selectively or en masse.
   
 * When class E imports class F, then the public methods
   of class F are visible in class E as public or joint methods.
   Class E has the ability to hide or rename them
   either selectively or en masse.
   
 Variables are always private.  Constants are treated like methods
 which require no arguments and always return the same value.
