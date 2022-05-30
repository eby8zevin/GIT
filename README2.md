`ssh-keygen` Result: id_rsa (private key) & id_rsa.pub (public key)
Connect to Server GitHub: https://github.com/settings/keys
Test SSH: `ssh -T git@github.com`
`git remote`
Add Remote Repository: `git remote add <nameremote/origin> ssh-url`
`git remote get-url <nameremote/origin>`
`git remote rm <nameremote/origin>`

`git push <nameremote> <localbranch>`
`git push <nameremote> <localbranch>:<remotebranch>`
`git push <nameremote> --all`
`git push --delete <nameremote/origin> <namebranch>`

`git clone <urlrepository>`