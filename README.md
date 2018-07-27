<p align="center">
  <img src="https://raw.githubusercontent.com/tomas/jix/master/screenshot.png" alt="Jix log view" />
</p>

`jix` is a command line, standalone client for Git, focused on commit insertion rather than just navigation. In other words, it's meant to help you manage your commit history and craft better commits, without having to type any commands by hand.

It's similar to `tig` but different in a few ways:

 - It lets you stage or unstage files *partially*, on a line-by-line basis. 
 - It lets you amend to your latest commit in case you missed something, or squash until a certain point.
 - It has great mouse support. You can click on commits or files, and bring context menus by right clicking on them.
 - It has a good keyboard support as well. You can drive most of the UI simply with your arrow keys, tab and spacebar. Yep, no need to remember which key shows the staging area.
 - It uses `libgit2` under the hood which means it's a) usually faster and b) doesn't depend on your local installation of `git`.
 - It's distributed as a single fat binary, so besides libc there are no other dependencies.

And it's coming soon to a terminal near you. :)
