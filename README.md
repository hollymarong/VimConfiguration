# Doricha Vimrc

Doricha is my personal Vim configurations and some plugins.

# Usage

## Installation and Requisites

### Windows Version:

1. BACKUP your `_vimrc` and `vimfiles` folder.

2. Clone this repository to vim home directory.

		$ git clone git@github.com:allotory/doricha.git vimfiles

	or using the following command to clone plugins directly and Ignore step 4:

		$ git clone --recursive git@github.com:allotory/doricha.git vimfiles

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

		$ git clone git@github.com:allotory/doricha.git ~/.vim

	or using the following command to clone plugins directly and Ignore step 4:

		$ git clone --recursive git@github.com:allotory/doricha.git ~/.vim

3. Other steps is the same as the windows version.

# Plugin list

1. [Vundle.vim][1] - Vundle is a Vim plugin manager.

2. [auto-pairs][2] - Insert or delete brackets, parens, quotes in pairs.

3. [molokai][3] - Molokai color scheme for Vim.

4. [nerdtree][4] - A tree explorer plugin for vim.

5. [syntastic][5] - Syntax checking hacks for vim.

6. [tagbar][6] - A class outline viewer for Vim.

7. [vim-airline][7] - Lean & mean status/tabline for vim.

# License

The MIT License.

# Contact

Enjoy it.

[1]: https://github.com/VundleVim/Vundle.vim
[2]: https://github.com/jiangmiao/auto-pairs
[3]: https://github.com/tomasr/molokai
[4]: https://github.com/scrooloose/nerdtree
[5]: https://github.com/scrooloose/syntastic
[6]: https://github.com/majutsushi/tagbar
[7]: https://github.com/vim-airline/vim-airline