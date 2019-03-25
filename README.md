# Uses

> It's use or be used my dudes

### 💾 Download these boyos
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Docker](https://www.docker.com/)
- [Hyper](https://hyper.is/)
- [VS Code](https://code.visualstudio.com/)
- [Figma](https://www.figma.com/downloads/)
- [Slack](https://slack.com/downloads/)

### 🌳 Setting up git credentials with WSL
1. Make sure [git](https://git-scm.com/) is installed
2. run `git config --global credential.helper "/mnt/c/Program\\ Files/Git/mingw64/libexec/git-core/git-credential-manager.exe"`
3. invoke a git function, e.g. `git add .`
4. The credential helper should popup asking for your git information

### Installing NVM
https://github.com/creationix/nvm#install--update-script

### Installing oh-my-zsh plugins
Great [tutorial](https://bit.ly/2U8ztVd) written by Mikhail Evdokimov

### zsh gotcha
Did you `cd ~` and don't know how to get back to your user account? It's as simple as:
```
cd ../../mnt/c/users/USER_NAME
```