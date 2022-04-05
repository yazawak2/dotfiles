## Installation
### Git
```
# clone
git clone git@github.com:yazawak2/dotfiles.git
cd dotfiles

# backup
cp ~/.gitconfig{,.backup.$(date +"%Y%m%d%H%M%S")}
ls -la ~/ | grep gitconfig

# create symbolic link
rm -f ~/.gitconfig
ln -s $(pwd)/git/.gitconfig ~/.gitconfig
```
