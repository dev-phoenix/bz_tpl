# useful bush commads
``` bash

ssh -v git@github.com:dev-phoenix/makeup-workspace.git
ssh-add -L # list of keys added to ssh agent
git remote -v # git origin
ssh -T git@github.com # git hello test
eval "$(ssh-agent -s)" # starts ssh agent in background
ssh-add ~/path_to_your_private_git_ssh_keys # add private key to ssh agent
ssh -T git@github.com # git hello test
```