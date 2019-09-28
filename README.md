# val-linux-config
My config files for the Linux tools I use daily

	$ cp val-linux-config/tmux.conf ~/.tmux.conf
	$ cp val-linux-config/vimrc ~/.vimrc

Install vim Vundle:

	$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

Lauch vim and then run :PluginInstall

Install tmux tpm

	$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

Reload tmux (or tmux source ~/.tmux.conf)
Then press prefix + I to install the plugins.
