
# Allowed Python Packages

The `ALLOWED_PYTHON_PACKAGES.txt` file lists Python packages that addons can request to be installed.

New packages can be added by opening an [Issue].

<br/>

## Format

The configuration doesn't follow any Python manifest format; it's just a simple text file where each non-empty and non-comment line is interpreted as a Python package.

Packages cannot be declared with a version nor wildcards.

[Issue]: https://github.com/FreeCAD/FreeCAD-addons/issues/new/choose
