<p align="center">
  <img src="https://raw.githubusercontent.com/tomas/jix/master/jix-screencast-2.gif" alt="Jix quick demo" />
</p>

`jix` is a terminal-based, standalone client for Git, focused on commit insertion (rather than simply browsing or inspection). In other words, it's meant to help you manage your history and craft better commits in a simple way, without having to type any commands by hand.

 - It lets you quickly stage or unstage *partial sections* of your files, on a line-by-line basis. 
 - It lets you amend to your latest commit in case you missed something, or squash until a certain point.
 - It has great mouse support. You can click on commits or files, and bring context menus by right clicking on them.
 - It has a good keyboard support as well. You can drive most of the UI simply with your arrow keys, tab and spacebar. Yep, no need to remember which key shows the status view.
 - It uses `libgit2` under the hood which means it doesn't depend on your local installation of `git`
 - It's distributed as a single fat binary, so besides libc and libm there are no other dependencies.

It draws a lot of inspiration from `tig`, but also from graphical tools like `gitg` and `GitX`.
