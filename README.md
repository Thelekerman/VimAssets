# VimAssets
Personal vim configuration files

## Instalation (Linux)
#### Step 1:
If .vim/ folder doesn't exists into your home directory, do.
```
cd ~
mkdir .vim
```
#### Step 2:
Clone the repo to some directory.
```
cd path/to/some/directory
git clone "https://github.com/Thelekerman/VimAssets.git"
```
#### Step 3:
Copy .vim files from repo.
```
cd path/to/repo
cp -R autoload colors doc plugged ~/.vim
```
#### Step 4:
If .vimrc doesn't exists, do:
```
cd path/to/repo
cp .vimrc ~
```
If .vimrc already exists just copy the content of repo's .vimrc to it.
