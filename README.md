Installation:

	git clone https://github.com/lihararora/dotvim.git

Create symlinks:

	ln -s ~/.vim/vimrc ~/.vimrc
	ln -s ~/.vim/gvimrc ~/.gvimrc

Update all submodules:

	cd .vim
	git submodule init
	git submodule update

NOTE: Always add new plugins as your dotvim repo's submodules! Here how:
	cd bundle
	git submodule add <url_to_the_plugin>
