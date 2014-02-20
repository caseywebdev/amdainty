# amdainty

A small, simple AMD module resolver for use in single-file, AMD-style projects.

## Usage

Simply include `amdainty.js` file before any of your `define` statements. It
will create `define` and `require` shims that do the bare minimum job of
including dependencies.
