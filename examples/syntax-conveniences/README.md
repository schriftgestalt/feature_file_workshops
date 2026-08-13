# Feature File Syntax Convenience Examples

These examples demonstrate syntax that reduces repetition, improves locality,
or provides clearer shorthand without adding new OpenType layout capabilities.

- **`deletion.fea`** - Direct and contextual glyph deletion
- **`lookups.fea`** - Standalone lookup definitions and optional closing labels
- **`multiple-languages.fea`** - Selecting multiple languages in one statement
- **`class-based-multiple-substitution.fea`** - Direct and contextual class-based multiple substitution
- **`lookupflag-reset.fea`** - Resetting lookup flags with an empty statement

The examples test syntax only. A compiler must additionally enforce semantic
requirements such as matching class lengths and a single marked deletion target.
