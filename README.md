tree-sitter grammar for CSS-in-JS.

clone this repo into a directory where it'll be a sibling of [`tree-sitter-css`](https://github.com/tree-sitter/tree-sitter-css).

```
[me@pc: ~/repos]$ ls
tree-sitter-css tree-sitter-css-in-js
```

this doesn't build due to problems with tree-sitter-css using an external scanner.  see [#1808](https://github.com/tree-sitter/tree-sitter/issues/1808).  help
update: this builds with the scanner taken from tree-sitter-css but that's not a great solution!
