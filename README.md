#GC

Note that this requires [GD](https://github.com/czipperz/gd).

This program allows for you to easily git commit. You can specify files or allow it to automatically commit all of them.

It clears the screens, `gd`s, then prompts for a commit message.

There are two options available:
* `-d` (or `--dont`) which causes it to NOT call `git reset HEAD` for all inputted files.
* `-h` (of `--help`) brings up the help.

Here is how to easily `git commit` all your files:
<pre>
$ gc
# Then it lets you type a commit message...
</pre>

Here is how to easily `git commit` one file:
<pre>
$ gc README.md
# Then it lets you type a commit message...
</pre>

Here is how to easily `git commit` multiple files:
<pre>
$ gc README.md install gc   #Fully commits this repository
# Then it lets you type a commit message...
</pre>

Example:

![Image: http://i.imgur.com/Aq9yoWg.png](http://i.imgur.com/Aq9yoWg.png)
