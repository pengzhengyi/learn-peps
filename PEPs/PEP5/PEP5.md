# PEP 5 – Guidelines for Language Evolution

This PEP introduces the guidelines for introducing backward-incompatible behavior
to Python.

> Backward incompatible behavior is a major deviation in Python interpretation
from an earlier behavior described in the standard Python documentation.

## Steps For Introducing Backwards-Incompatible Features

1. Propose backwards-incompatible behavior in a PEP
2. If PEP is accepted, provide an alternative for accomplishing removed or changed behavior
3. Deprecate the construct in documentation
4. Add **parser warning** when deprecated construct is used
5. **One year transition period** between the release of transitional version of Python and the
backwards incompatible version
