# awesome_4_ben

ben's awesome WM dotfiles, if you clone this, PLEASE don't expect me to 'hold your hand' i'm in NO way a lua or awesome wm expert! anything outside gentoo gnu/linux or arch linux i cannot support you with this setup. 

steps (PLEASE follow before seeking help,support, etc.):

sudo pacman -S (emerge -av) awesome vicious nm-applet blueman picom zsh gentoo-zsh-completions zsh-completions zsh-syntax-highlighting vim

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

git clone https://github.com/bfitzgit23/awesome_4_ben

cd awesome_4_ben

cp -v .Xresources ~/.Xresources

cp -rv .urxvt ~/.urxvt

cp -rv .oh-my-zsh ~/.oh-my-zh

cp -v .zshrc ~/.zshrc 

cp -rv awesome ~/.config/awesome

sudo cp -rv Surfn* /usr/share/icons

sudo cp -rv Colloid* /usr/share/themes

then logout and login to awesome and ENJOY!
