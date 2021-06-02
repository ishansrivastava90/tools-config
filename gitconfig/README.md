This repo contains global and system git configs for derivation of repo specific settings. 

#********************************************************************************************

Rename 'gitconfig.global' to .gitconfig and then use `git config --global <setting>` to update the config.
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup


Create an empty repo on github.
Run the cmd below to add the remote repo
git remote add origin https://github.com/ishansrivastava90/repo-name.git

Cmd for local branch to track the remote branch on remote ('origin')
git push --set-upstream origin master