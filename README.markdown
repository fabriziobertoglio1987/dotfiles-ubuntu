My NeoVim setup for React Native on Ubuntu 20.4, includes:

- Java/Android:
  - [fzf.vim](https://github.com/junegunn/fzf.vim) the best vim plugin!
  - [Treesitter](https://github.com/nvim-treesitter/nvim-treesitter) syntax highlighting
  - Tags for navigating Android Sdk and many other libraries
  - FZF to search with Ripgrep, Open Files, Search Tags and History
  - Tags to do autoimports
- youcompleteme language server
- tmux to manage different type of work sessions:
  - start session to work on React Native master and automatically start the emulator/server/android build
  - start session to change dotfiles
  - start session to work on other React Native projects etc..etc..
- zsh with syntax highlighting, autcomplete and history completion
- snippets (default and custom)
- [line autocompletion](https://github.com/junegunn/fzf.vim#custom-completion) - autocomplete an entire line
- [VimTmuxRunner](https://github.com/christoomey/vim-tmux-runner) to run cli commands from vim in a tmux pane

The basic setup was taken from [Upcase](https://thoughtbot.com/upcase/) courses on vim/tmux.
