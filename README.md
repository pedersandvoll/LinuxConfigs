# Tmux and Nvim setup
## Tmux
First of all download tmux with you're desired package manager.  
First clone .tmux.conf down into you're ~/ folder.  
Then clone the .tmux folder down into the same ~/ folder.  
Run this command `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`.  
In you're terminal write `tmux`.  
And then press <kbd>Ctrl</kbd> + <kbd>s</kbd> and write `source-file ~/.tmux.conf`.  
Exit the tmux session and open a new one, run this <kbd>Ctrl</kbd> + <kbd>s</kbd> + <kbd>I</kbd> to install the plugins.  
Now you are done!

## Nvim
First download Neovim.  
clone down the nvim folder into you're ~/.config folder.  
Then download ripgrep with you're desired package manager.  
Go into the ~/.config/nvim/init.lua file and run <kbd>:</kbd> + <kbd>w</kbd> to download the plugins.  
Edit the keybinds if you would like, then you are done!
