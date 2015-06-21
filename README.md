# My tmux settings

Sources:
- [Chris Hunt - Impressive Ruby Productivity with Vim and Tmux - Ancient City Ruby 2013](https://www.youtube.com/watch?v=9jzWDr24UHQ) 
- [Configuring Your Linux for Development With Zsh, Tmux, and Vim](https://www.codementor.io/linux/tutorial/configure-linux-toolset-zsh-tmux-vim)
- [A tmux Crash Course](https://robots.thoughtbot.com/a-tmux-crash-course)

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
