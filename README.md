Set your username `git config --global user.name "Your Name"`
<br>
Set your email address `git config --global user.email "your@email.com"`
\
Check all configuration `git config --list --show-origin`

Create repository `git init`
\
Check status `git status`

Add file from working_directory to staging_index `git add <namefile>` or `git add <namefile> <namefile>` or all file `git add .` 
\
Commit to repository `git commit -m "commit message"`

Compare commit `git diff` or `git diff <hash1> <hash2>` or open code_editor `git difftool <hash1> <hash2>`

Undo changes in working_directory `git restore <namefile>`
\
Undo changes in staging_index `git restore --staged <namefile>`

Cancel all new file `git clean -f`

See history `git log` or `git log --oneline` or `git log --oneline --graph`
\
See detail commit `git show <hash>` or `git show HEAD`

Reset commit a HEAD:
\
--soft `git reset --soft <hash>`
\
--mixed (default) `git reset --mixed <hash>`
\
--hard `git reset --hard <hash>`

Update/merge file in one commit `git commit --amend -m "commit message"`

View file previous version `git checkout <hash> -- <namefile>`
\
View snapshot `git checkout <hash>`
\
back to a HEAD `git checkout master/main`

Revert commit `git revert <hash>`

Find out WHO detail changed file `git blame <namefile>`
\
View changes `git show <hashblame>`

Alias `git config --global alias.ko commit` or `git config --global alias.komit commit` or two words `git config --global alias.logone "log --oneline"`

Hidden file, create file `.gitignore`

View name branch `git branch --show-current`

[Source](https://docs.google.com/presentation/d/1PQEVGpmhj_3ASopsP-48NRkjilOcOuwWr_gDtwB1IEg/edit?usp=sharing)
