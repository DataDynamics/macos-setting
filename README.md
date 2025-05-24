# macos-setting

macOS 설정


## Installation

### Brew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 필수 라이브러리 설치

```
brew install htop tree wget
```

### Oh My Zsh + Power Level 10K

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git "${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k"
echo "typeset -g POWERLEVEL9K_DIR_PATH_ABSOLUTE=true" >> .p10k.zsh
```

### pyenv

```shell
brew update
brew install pyenv
```

### nvm

https://github.com/nvm-sh/nvm

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```

### sdkman

```shell
curl -s "https://get.sdkman.io" | bash
sdk install java
sdk install maven
sdk install gradle
sdk install ant
```

### rbenv

```shell
brew install rbenv
```

### MCS

```shell
# sdk install mcs 0.7.3

# mcs search maven
Searching for maven...
Found 10746 results (showing 20)

  Coordinates                                             Last updated
  ===========                                             ============
  org.nasdanika.core:maven:2025.3.0                       30 Mar 2025 at 12:56 (KST)
  org.apache.tomee.maven:maven:10.0.1                     20 Mar 2025 at 22:18 (KST)
  org.apache.maven:maven:4.0.0-rc-3                       05 Mar 2025 at 18:47 (KST)
  net.microfalx.maven:maven:0.8.2                         11 Feb 2025 at 21:01 (KST)
  au.com.dius.pact.provider:maven:4.7.0-beta.0            04 Dec 2024 at 07:49 (KST)
  org.openjax.maven:maven:0.5.0                           27 Feb 2024 at 15:55 (KST)
  com.epam.drill.agent.runner:maven:0.3.4                 03 Nov 2023 at 20:05 (KST)
  net.ssehub.easy.instantiation:maven:1.3.5               04 Oct 2023 at 23:41 (KST)
  com.ksc.mission.base:maven:1.2.6.7                      28 Sep 2023 at 18:56 (KST)
  org.quattor.maven:maven:1.62                            10 Jul 2023 at 19:29 (KST)
  io.github.liuweile:maven:4.0.1                          23 Mar 2023 at 16:39 (KST)
  org.jboss.forge.addon:maven:3.10.0.Final                14 Jun 2022 at 09:03 (KST)
  io.provenance.asset:maven:0.0.0-test2                   12 May 2022 at 06:50 (KST)
  io.github.drewctaylor:maven:0.0.2                       03 Apr 2022 at 09:40 (KST)
  com.10duke.client.parent:maven:1.1.0                    15 Feb 2022 at 23:21 (KST)
  net.officefloor.maven:maven:3.40.0                      12 Aug 2021 at 04:47 (KST)
  com.github.rutledgepaulv:maven:1.2                      28 Mar 2021 at 10:10 (KST)
  io.oss84.geotools.maven:maven:24.2-oss84-1              22 Feb 2021 at 00:44 (KST)
  net.lecousin.framework.application-loader:maven:0.1.0   08 Mar 2020 at 12:35 (KST)
  net.lecousin.core.loaders:maven:0.18.0                  16 Feb 2020 at 20:21 (KST)
  
  # mcs class-search -f picocli.CommandLine
Searching for artifacts containing picocli.CommandLine...
Found 18676 results (showing 20)

  Coordinates                                      Last updated
  ===========                                      ============
  info.picocli:picocli-jpms-module:4.0.0-alpha-3   13 May 2019 at 21:19 (KST)
  info.picocli:picocli-jpms-module:4.0.0-alpha-2   19 Apr 2019 at 18:17 (KST)
  info.picocli:picocli:1.0.1                       29 Aug 2017 at 00:57 (KST)
  info.picocli:picocli:1.0.0                       27 Aug 2017 at 00:40 (KST)
  info.picocli:picocli:0.9.8                       07 Aug 2017 at 02:02 (KST)
  info.picocli:picocli:0.9.7                       08 Jun 2017 at 01:22 (KST)
  info.picocli:picocli:0.9.6                       25 May 2017 at 01:46 (KST)
  info.picocli:picocli:0.9.5                       09 May 2017 at 22:09 (KST)
  info.picocli:picocli:0.9.4                       04 May 2017 at 11:18 (KST)
  info.picocli:picocli:0.9.3                       28 Apr 2017 at 00:43 (KST)
  info.picocli:picocli:0.9.2                       28 Apr 2017 at 00:32 (KST)
  info.picocli:picocli:0.9.1                       28 Apr 2017 at 00:30 (KST)
  info.picocli:picocli:0.9.0                       28 Apr 2017 at 00:06 (KST)
  org.primefaces:primefaces-cli:15.0.3             29 Mar 2025 at 01:34 (KST)
  org.primefaces:primefaces-cli:15.0.2             21 Mar 2025 at 20:56 (KST)
  org.primefaces:primefaces-cli:15.0.1             13 Mar 2025 at 02:23 (KST)
  org.primefaces:primefaces-cli:15.0.0             18 Feb 2025 at 00:49 (KST)
  org.primefaces:primefaces-cli:14.0.12            17 Feb 2025 at 23:50 (KST)
  org.primefaces:primefaces-cli:14.0.11            29 Jan 2025 at 04:13 (KST)
  org.primefaces:primefaces-cli:15.0.0-RC2         17 Jan 2025 at 22:52 (KST)
```

## Github

```bash
git config --global user.name 김병곤
git config --global user.email fharenheit@gmail.com
git config --global credential.helper store
```

## .zshrc

```shell
username=`id -un`

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
fpath=(/Users/${username}/.docker/completions $fpath)
autoload -Uz compinit
compinit
# End of Docker CLI completions

# THIS MUST BE AT THE END OF THE FILE FOR SDKMAN TO WORK!!!
export JAVA_HOME=/Users/${username}/.sdkman/candidates/java/current
export SDKMAN_DIR="$HOME/.sdkman"
[[ -s "$HOME/.sdkman/bin/sdkman-init.sh" ]] && source "$HOME/.sdkman/bin/sdkman-init.sh"
```

## Maven Repository

`<USER_HOME>/.m2/settings.xml` 파일

```xml
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">

  <mirrors>
    <mirror>
      <id>central</id>
      <name>Open Cloud Engine Repo</name>
      <url>http://nexus.opencloudengine.org/repository/maven-public/</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
  </mirrors>
</settings>
```
