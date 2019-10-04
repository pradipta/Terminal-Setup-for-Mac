# Terminal-Setup-for-Mac
My custom terminal setup for MacBook

Install Homebrew. For that, run : 
```
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
You may need to install Command Line tool for X-Code before that.

```
  xcode-select --install
```

Install ZSH and oh-my-zsh : 

```
  brew install zsh
  
  sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

To run xsh shell, run: 
```
  zsh
```

To have additional features on ZSH, you need to edit the ```.zshrc``` file.

Install zsh-autosuggestions and zsh-syntax-highlighting:
```
brew install zsh-syntax-highlighting
brew install zsh-autosuggestions
```
Add these lines to the .zshrc :
```
source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh
source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```
Make sure to run ```source ~./.zshrc``` after addition of new features for it to load.

Check the .zshrc file to get the required features.

