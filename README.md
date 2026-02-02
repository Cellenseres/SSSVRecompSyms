Space Station Silicon Valley: Recompiled Symbols
This repo contains the symbol files used by the recompiler to generate the code for the Space Station Silicon Valley: Recompiled projec. These files were generated from the SSSV decompilation project, which allows the recompilation project to use function and variable names from the decompilation to help with writing patches.

This is a separate repo from the main one so that mods can reference just this repo instead of the recompilation's entire repo. It also helps avoid bloating the main repo's size and history, as the symbol files are very large.

The syms.toml file contains function definitions that the recompiler uses to find code in the ROM during the initial recompilation. The syms.toml and datasyms.toml files are all used during patch recompilation to allow the recompiler to resolve references to functions and variables in patch code. This allows patches to be written by copying in matched functions from the decompilation and tweaking them.


The commit of the decompilation that these symbols were generated from can be found here.