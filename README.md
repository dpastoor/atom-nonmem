atom-nonmem
===========

A package for managing nonmem through the atom editor.

Atom is a cross-platform, free, open-source editor, hackable editor making it ideal for working with files and adding functionality to a typical workflow.

# Core functionality
Some immediate workflow enhancements provided by atom-nonmem are:

1) `syntax highlighting` - making it easy to navigate files visually and catch errors (eg a misspelling like `THATA` will not be highlighted but `THETA` will, thus causing the misspelling to stand out.)

2) `snippets` - prebuilt blocks of code that automatically moves your cursor reduces typing and speeds up iteration. For example, by typing `simn` then pressing `tab`, the statement

`$SIM () ONLYSIM NSUB = ` will be added with the cursor placed between the `()` to quickly type in a random seed then by pressing `tab` it will take you to past the `=` to insert the number of NSUBs you would like.

![nsub](assets/simn.gif)

3) NOT IMPLEMENTED - additional functionality such as automatic refactoring, model file duplication and updates,

4) Use of atom editor functionality. Things like multiple cursors, project management, todos, fuzzy file search, and remote editing capabilities make atom much more powerful than your typical editor.
