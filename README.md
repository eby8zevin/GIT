`git config --global user.name "Your Name"`
`git config --global user.email "your@email.com"`
`git config --list --show-origin`

`git init`
`git status`

`git add <namefile>` | `git add <namefile> <namefile>` | `git add .` 
`git commit -m "commit message"`
`git diff`
`git diff <hash1> <hash2>`
`git difftool <hash1> <hash2>`

`git restore <namefile>`
`git restore --staged <namefile>`

`git clean -f`

`git log`
`git log --oneline`
`git log --oneline --graph`
`git show <hash>`
`git show HEAD`

`git reset --soft <hash>`
`git reset --mixed <hash>`
`git reset --hard <hash>`

`git commit --amend -m "commit message"`

`git checkout <hash> -- <namefile>`
`git checkout <hash>`
`git checkout master/main`

`git revert <hash>`

`git blame <namefile>`
`git show <hashblame>`

`git config --global alias.ko commit`
`git config --global alias.komit commit`
`git config --global alias.logone "log --oneline"`

`git branch --show-current`