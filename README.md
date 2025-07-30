
This repository contains all code necessary to implement a wikitext tree-sitter parser.
This fork makes all essential nodes
visible for syntax highlighting

# [Tree-Sitter](https://tree-sitter.github.io/tree-sitter/)
According to tree-sitter's website:
> Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

> - General enough to parse any programming language
> - Fast enough to parse on every keystroke in a text editor
> - Robust enough to provide useful results even in the presence of syntax errors
> - Dependency-free so that the runtime library (which is written in pure C) can be embedded in any application

## Documentation
- Link to page explaining how to write parsers in the `grammar.js` file: [Tree-Sitter creating parsers documentation](https://tree-sitter.github.io/tree-sitter/creating-parsers)
- Documentation on how to use the resulting parser in Python with the `tree-sitter` python module [Tree-Sitter using parsers in Python](https://tree-sitter.github.io/py-tree-sitter/index.html)


## Credits

The parser is written by [Miel Peeters](https://github.com/mielpeeters) at [GhentCDH](https://www.ghentcdh.ugent.be/) to parse and convert a MediaWiki website.
