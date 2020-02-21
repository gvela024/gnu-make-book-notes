# Intro
https://www.gnu.org/software/make/manual/html_node/Introduction.html#Introduction
`Makefile` or `name.mk` tells `make` what to do.

The example will be compiling some C and H files. It will compile the C files into object files. Object files must be recompiled whenver the corresponding C file changes. When an H file changes, every C file that includes that H file must be recompiled to be safe. When any object file is recompiled, the entire program must be linked to produce a new executable.

# What a rule looks like
https://www.gnu.org/software/make/manual/html_node/Rule-Introduction.html#Rule-Introduction
