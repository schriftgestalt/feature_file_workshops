# Conditional Preprocessing Examples

These examples demonstrate the `#ifdef`, `#ifndef`, and `#endif` conditional
preprocessing directives.

- **`variable-and-static.fea`** - Select code for variable and static builds

The directives are evaluated before normal feature file parsing. The grammar
validator recognizes directives but does not choose a preprocessor branch.
