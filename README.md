# macos-setting

macOS 설정


## Installation

### pyenv

```
brew update
brew install pyenv
```

### nvm

https://github.com/nvm-sh/nvm

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```

### sdkman

```
curl -s "https://get.sdkman.io" | bash
sdk install java
sdk install maven
sdk install gradle
sdk install ant
```

### rbenv

```
brew install rbenv
```

## Github

```
git config --global user.name 김병곤
git config --global user.email fharenheit@gmail.com
git config --global credential.helper store
```

## .zshrc

```
source ~/powerlevel10k/powerlevel10k.zsh-theme

# To customize prompt, run `p10k configure` or edit ~/.p10k.zsh.
[[ ! -f ~/.p10k.zsh ]] || source ~/.p10k.zsh

eval "$(/opt/homebrew/bin/brew shellenv)"

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

eval "$(rbenv init - --no-rehash zsh)"

export PYENV_ROOT="$HOME/.pyenv"
[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init - bash)"
eval "$(pyenv virtualenv-init -)"

# The following lines have been added by Docker Desktop to enable Docker CLI completions.
fpath=(/Users/fharenheit/.docker/completions $fpath)
autoload -Uz compinit
compinit
# End of Docker CLI completions


#THIS MUST BE AT THE END OF THE FILE FOR SDKMAN TO WORK!!!
export JAVA_HOME=/Users/fharenheit/.sdkman/candidates/java/current
export SDKMAN_DIR="$HOME/.sdkman"
[[ -s "$HOME/.sdkman/bin/sdkman-init.sh" ]] && source "$HOME/.sdkman/bin/sdkman-init.sh"
```
