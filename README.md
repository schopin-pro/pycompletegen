# `pycompletegen`

This small project has one simple, single goal: generate decent *standalone*
completion scripts for *unmodified* Python scripts.

We want the completion scripts to be standalone because it makes it easier to
distribute them without the users having to install a new dependency.

We don't want to have to modify the Python scripts, because we might not be in
a position to, e.g. those scripts are part of a repo you don't have write
access to.

## Usage

`./pycompletegen myscript > $HOME/.config/fish/completions/myscript.fish`


