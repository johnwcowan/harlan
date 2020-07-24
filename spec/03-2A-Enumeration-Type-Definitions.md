**3-2A: Enumeration Type Definitions.  There shall be types that are definable in programs by enumeration of their elements. The elements of an enumeration type may be identifiers or character literals. Each variable of an enumeration type may be restricted to a contiguous subsequence of the enumeration.**

In a Unicode world, a character type doesn't make much sense,
so the elements of an enumeration type are identifiers.
Each one is associated with an ordinal number.

Differene enumeration types can contain elements that
are represented by the same identifier,
but the elements of a single enumeration type must
be distinct.
