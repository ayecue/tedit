# TEdit

Vim like text editor for the game Grey Hack.

Features:
- Vim commands like search etc

Plugins:
- CodeEditor
	- Syntax highlighting
	- Custom syntax check
	- Custom interpreter

Other plugins comming soon.

# Demo

[![TEdit Demo](/assets/demo.gif?raw=true)](https://www.youtube.com/watch?v=waPEtJLboRw)

# Install

Uses [greybel-js](https://github.com/ayecue/greybel-js) for transpiling.

1. Nightly: `greybel tedit.src build --installer` or Non nightly: `greybel tedit-non-nightly.src build --uglify`
2. Copy installer files into GreyHack
3. Compile installer files to ingame binary (this will automatically create all the files)
4. Compile tedit.src to ingame binary
