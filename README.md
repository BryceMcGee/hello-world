# Notes from Learnin'
### Added SSH file to ~/bin/start-ssh-agent.sh
####     This prevents need to use passwords all the time 
### Installed ASDF, via ohMyZSH plugin

### Installed go v1.18 via asdf for the hello-world project  

### created a paths.d directory, added a file named bryce, added 
#### ~/.asdf./shims
#### ~/bin
#### /usr/locak.bin
### Then added the recommended go extentions to vs code

List of steps to configure a linux dev environment (Without context the list is somewhat vague. It was originally created to spark memory of the process to someone that has already gone through it, rather than fully explain step by step)

1. install/configure zsh & oh-my-zsh
2. starship (terminal prompt)
3. install nerd font & configure in terminal
4. install ASDF (and configure in .zshrc)
5. install go via ASDF (asdf install golang 1.18.1)
6. configure some ENV vars in .zshrc for asdf & go
7. install GoLand
8. install latest Git
9. create ed25519 ssh key
10. configure ssh-agent
11. git config with some global settings (username, email, difftool, etc)
12. create a new github repo -> exercism
13. clone exercism git repo to ~/projects/exercism
14. configure GoLand to use the .asdf/installs/golang/1.18.1/go path for the SDK
15. configure GoLand to use the Nerdfont
16. configure GoLand with a few extra extensions and nice-to-have settings
17. install the exercism CLI
18. configure the exercism CLI to use your `~/projects/exercism` as your "workspace"
19. download the first exercism exercise, and commit it


Making changes to test github in VS Code