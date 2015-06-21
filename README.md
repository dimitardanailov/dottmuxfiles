# My tmux settings

Sources:
- [Chris Hunt - Impressive Ruby Productivity with Vim and Tmux - Ancient City Ruby 2013](https://www.youtube.com/watch?v=9jzWDr24UHQ) 
- [Configuring Your Linux for Development With Zsh, Tmux, and Vim](https://www.codementor.io/linux/tutorial/configure-linux-toolset-zsh-tmux-vim)

# Keep your dotfiles in git

```bash
git clone https://github.com/dimitardanailov/dotvimfiles ~/.tmux/
```

Create symbolic links so that `~/.tmux.conf` points to the ~/.tmux/tmux.conf file:

```bash
ln -s ~/.tmux/tmux.conf ~/.tmux.conf
```
