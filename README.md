# My tmux settings

Sources:
- [OpenBSD tmux](http://www.openbsd.org/cgi-bin/man.cgi/OpenBSD-current/man1/tmux.1?query=tmux&sec=1)
- [Chris Hunt - Impressive Ruby Productivity with Vim and Tmux - Ancient City Ruby 2013](https://www.youtube.com/watch?v=9jzWDr24UHQ) 
- [Configuring Your Linux for Development With Zsh, Tmux, and Vim](https://www.codementor.io/linux/tutorial/configure-linux-toolset-zsh-tmux-vim)
- [A tmux Crash Course](https://robots.thoughtbot.com/a-tmux-crash-course)
- [tmux Copy & Paste on OS X: A Better Future](https://robots.thoughtbot.com/tmux-copy-paste-on-os-x-a-better-future)
- [Love, Hate, & tmux](https://robots.thoughtbot.com/love-hate-tmux)
- [Rocking With Tmux, Tmuxinator, Guard, Zeus, and iTerm2 for Rails Development](http://www.railsonmaui.com/blog/2014/03/11/rocking-with-tmux-tmuxinator-and-iterm2-for-rails-development/)
- [Increased Developer Productivity with Tmux, Part 8: Copy mode.](http://minimul.com/increased-developer-productivity-with-tmux-part-8.html)

# Keep your dotfiles in git

```bash
git clone https://github.com/dimitardanailov/dotvimfiles ~/.tmux/
```

Create symbolic links so that `~/.tmux.conf` points to the ~/.tmux/tmux.conf file:

```bash
ln -s ~/.tmux/tmux.conf ~/.tmux.conf

# reloads the current tmux configuration (based on a default tmux config)
tmux source-file ~/.tmux.conf
```
