Create SSH `ssh-keygen`
\
Result: id_rsa (private key) & id_rsa.pub (public key)
\
Connect to Server GitHub https://github.com/settings/keys with public key
\
Test SSH `ssh -T git@github.com`

View remote repository `git remote`
\
View URL detail remote repository `git remote get-url <nameremote/origin>`
\
Add remote repository `git remote add <nameremote/origin> ssh-url`
\
Remove remote repository `git remote rm <nameremote/origin>`

Push with same branch `git push <nameremote> <localbranch>`
\
Push with different branch `git push <nameremote> <localbranch>:<remotebranch>`
\
Push all branch `git push <nameremote> --all`

Delete branch `git push --delete <nameremote/origin> <namebranch>`

Clone / download repository `git clone <urlrepository>`
\
Clone different folder with name repository `git clone <urlrepository> <namefolder>`

[Source](https://docs.google.com/presentation/d/1-niKm6ktEhS8gQTu4kTUrLJmYlcyBZ8TT1ldmW1XRHo/edit?usp=sharing)
