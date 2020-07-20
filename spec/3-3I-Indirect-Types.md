**3-3I: Indirect Types.  It shall be possible to define types whose elements are indirectly accessed. Elements of such types may have components of their own type, may have substructure that can be altered during execution, and may be distinct while having identical component values. Such types shall be distinguishable from other composite types in their definitions. An element of an indirect type shall remain allocated as long as it can be referenced by the program. [Note that indirect types require pointers and sometimes heap storage in their implementation.]**