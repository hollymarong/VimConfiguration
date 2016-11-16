VimConfiguration is my personal Vim configurations and some plugins.

# Usage

## Installation and Requisites

### Windows Version:

1. BACKUP your `_vimrc` and `vimfiles` folder.

2. Clone this repository to vim home directory.

		$ git clone git@github.com:hollymarong/Vimconfiguration.git vimfiles

	or using the following command to clone plugins directly and Ignore step 4:

		$ git clone --recursive git@github.com:hollymarong/Vimconfiguration.git vimfiles

3. Config `_vimrc` file add:

		if(has('win32') || has('win64'))
			source $VIM/vimfiles/vundle_vimrc
			source $VIM/vimfiles/basic_vimrc
		else
			source ~/.vim/vundle_vimrc
			source ~/.vim/basic_vimrc
		endif

4. Update plugins.

		$ git submodule init
		$ git submodule update

### Linux Version:

1. BACKUP your `.vimrc` and `.vim` folder.

2. Clone this repository to vim home directory.

		$ git clone git@github.com:hollymarong/Vimconfiguration.git ~/.vim

	or using the following command to clone plugins directly and Ignore step 4:

		$ git clone --recursive git@github.com:hollymarong/Vimconfiguration.git ~/.vim

3. Other steps is the same as the windows version.

