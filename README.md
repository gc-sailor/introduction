# Intro

What you need to start working/learning with GC Sailor.

# Dependencies

Python 3.6.7 (64-bit preferred): https://www.python.org/downloads/release/python-367/

Git: https://git-scm.com/downloads

(optional) GitHub Desktop: https://desktop.github.com/

# IDE (choose one)

PyCharm (Community version): https://www.jetbrains.com/pycharm/download/#section=windows

Atom: https://atom.io/

# Tutorials

Beginner's Python Guide: https://younglinux.info/python.php

Python Documentation: https://docs.python.org/3.6/

libtcod Roguelike Tutorial: http://rogueliketutorials.com/libtcod/1

# What to do? 

First of all, install the dependencies.
 * Start with Python. Download the executable and run it. Make sure to add Python to your PATH, either by installer or manually. 
 * Install Git. During installation, when choosing what to do with PATH, select the 2nd option to add Git to your PATH.
 * Check both Git and Python. Run your shell of choice (you can go with Bash that was installed during Git installation). Type "python" to check python, and type "git" to check git. 
 * Setup git config. Type "git config --global user.name "your_githib_username_here"" and "git config --global user.email "your_github_email_here"".
 
 Then you need to choose an IDE you're going to work in. PyCharm is powerful, but requires resources. Atom is more lightweight, but it doesn't have the wide variety of out-of-box features that PyCharm has. If all else fails, you can use Notepad++.
 
 After this, all you have to do is to follow the libtcod Roguelike Tutorial. 
 
 To install required libs for the first lesson, run the following command: "python -m pip install tcod"
 
 Whenever you see "import libtcodpy ..." in the tutorials, go for "import tcod ...". Tcod is the modern iteration of the libtcodpy port and has backwards compatibility, so the tutorial should work fine, even if some of it is deprecated.
 
 You can ignore the deprecation messages safely. Or you can go for "import libtcodpy" just as the tutorial tells you to and ignore the deprecation warnings from PyCharm. 
 
 While completing the tutorial, make your own private repo of the roguelike you're working on. Make sure to commit after every completed lesson. Completed lesson means that the game actually works as expected, don't commit untested code.
