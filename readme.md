# Required Software

## Ubuntu

### Chrome

### Cuda
```bash
sudo add-apt-repository ppa:graphics-drivers/ppa

sudo apt update

sudo ubuntu-drivers autoinstall

sudo apt install gcc-6

# Then install cuda and cudnn based on the version required by pytorch and tensorflow from office website
```

### Git
```bash
sudo apt install git
```
### Zsh
```bash
sudo apt install zsh
```

### Vim
```bash
sudo apt install vim
```

### Oh my zsh
```bash
sudo wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh

chsh -s /bin/zsh

# Then Reboot
```
#### Extension
 - [autojump](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)

```bash
git clone git://github.com/wting/autojump.git
cd autojump
./install.py

# in ~/.zshrc
plugins=(autojump)
```

 - web-search
 - extract
 - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# in ~/.zshrc
plugins=( [plugins...] zsh-syntax-highlighting)
```
 - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# in ~/.zshrc
plugins=(zsh-autosuggestions)
```


### Tmux
```bash
sudo apt install tmux
```

### Filezilla
```bash
sudo apt install filezilla
```

### Anaconda

### VS Code

#### Extension
 - Python
 - Anaconda Extension Pack
 - GitLens
 - Prototxt
 - YAML
 - Markdown All in One


### Sougou
```bash
sudo apt-get install fcitx-bin
sudo apt-get install fcitx-table

```


