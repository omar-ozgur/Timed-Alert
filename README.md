# Command Safe
A simple way to save and recall commands with short aliases

# How does it work?
Command Safe is a great tool when you find yourself commonly typing the same long commands. Why not save those commands to a short and convenient alias that you can recall at any time!

After installing the command-line tool, simply use the command `command-safe` or `csa` along with various arguments and flags to achieve the desired effects.

Here are some examples:

- Save a command to a new alias: `csa "my-alias" "my-command"`
- Execute a saved command: `csa "my-alias"`
- Show existing commands: `csa -s`
- Show verbose output: `csa -v`
- Delete a specific command: `csa -d "my-alias"`
- Clear all commands: `csa --clear`

# Installation
Install through pip with the command `pip install command-safe`

# Python Version Support
Command Safe works for Python installations with versions >= 2.6.
