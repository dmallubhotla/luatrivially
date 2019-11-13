# luatrivially

This provides a package `luatrivially` requiring Lua.

This effectively acts as a Lua-based rewrite / merge of https://github.com/pigpenguin/trivial and https://github.com/bgschiller/latex-therefore, both of which use a counter-based system to handle their randomisation.
For consistent use suitable for `latexmk` or other monitoring tools, set the seed using Lua's `math.randomseed()`.

Provides the functions `\triv` and `\thrf`, to be used like `\triv 2 + 2 = 5. \thrf 5 + 5 = 2`.