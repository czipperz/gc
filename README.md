#GC

Note that this requires [GD](https://github.com/czipperz/gd)

This program allows for you to easily git commit. You can specify files or allow it to automatically commit all of them.

Here is how to easily `git commit` all your files:
<pre>
$ gc              # short for `$ clear; gd;           g add -A`
# Then it lets you type a commit message...
</pre>

Here is how to easily `git commit` one file (or more if you specify them):
<pre>
$ gc README.md    # short for `$ clear; gd README.md; g add README.md`
# Then it lets you type a commit message...
</pre>
