# Description

**Prevent Corruption** [1] is a simple Sublime Text 3 plug-in which will
try hard to prevent situations on which files may be corrupted because
of a misinterpretation on how ST works, or just caused by human
distraction.

**Fake Clones**

A fake clone is a file that has been opened in more than one
view/tab/column/group/window and does not share a buffer with the first
instance of it. Changes in one instance of the file opened will
overwrite the other instance, making us lose changes if we don't notice
it.​ Specially happens when we have many windows opened, or when the
amount of opened files is really huge.​ There are a number of situations
on which you may be able to open "fake clones" in the same window.. or
in other windows... This package tries hard to Prevent that.

[1] ​I'm sorry this is not about political corruption.

**Real Clones**

To create a "clone" of a view, you should use: Main Menubar -\> File -\>
"New File Into View". This will open other view/tab that is a real clone
of the file you are writing, and changes to any of the view/tabs will be
reflected in all the instances. Some of us consider the name of that
menuitem("New File Into View") is not appropriated, and opened an issue
to try to call attention, please visit:
https://github.com/SublimeTextBugs/Issues/issues/34

# Bugs

Instead of preventing the opening of the "fake clone", it would be nice
to just close the "fake clone" and create a real clone. Problem is that
currenlty there is no way to move a "real clone" from one window to
another. Then, we will likely fail at this for now..

# Installation

Download or clone the contents of this repository to a folder named exactly as the package name into the Packages/ folder of ST.

# Source-code

https://github.com/titoBouzout/PreventFakeClones

# Forum Thread​​

http://www.sublimetext.com/forum/viewtopic.php?f=3&t=16019

# License

See license.txt

  [Sublime Text 3+]: http://www.sublimetext.com/
  [Package Control 2+]: https://sublime.wbond.net/installation
