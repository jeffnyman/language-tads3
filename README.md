TADS 3 Language Grammar for Atom

- Created by Jeff Nyman <jeffnyman@gmail.com>
- https://github.com/jeffnyman/language-tads3
- https://atom.io/packages/language-tads3

This package permits syntax coloring of [TADS 3][t3] source code in the [Atom][] editor. This should also work with compatible syntax colorers, like TextMate 2 or Sublime, with some appropriate changes for the particulars of how grammar files are specified.

Note that this package does not deal with [TADS 3][t2].

[t3]: http://tads.org/
[t2]: http://tads.org/tads2.htm
[atom]: https://atom.io/

This language extension correctly handles:

- Comments
- Strings (double and single)
- String escape sequences
- String interpolation
- Operators
- Regular expressions
- Preprocessor Statements
- Keywords
- Object and function definitions

This language extension is not currently providing coloring for TADS 3 library elements, such as classes from ADV3 or ADV3Lite. The initial release is simply to make sure that the TADS language itself is covered reasonably well.

This language extension does not add the ".h" files to the recognized types, even though TADS 3 does use such files. Atom, by default, should recognize such files as C++ and that should generally give you good enough highlighting.
