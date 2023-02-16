# Git ALL Status

`git init` git initialaise kora

`git add .` git add kora

`git status` change kora file check kora

`git commit -m "Inisial Start"` comment kora

`git branch -M main` main default branch create kora

`git remote add origin https://github.com/jowelht/git-commit.git` remote path bole dowa

`git push origin main` main branch a push kora

---

`git clone https://github.com/jowelht/.....`

---

`git checkout -b deploy` new branch deploy name er create kora

`git branch` kon kon branch ache ota check kora

`git merge main` main branch er sath merge kora same data gula nia asa

`git push origin deploy` deploy branch a ai data push kora.

`git checkout main` branch back jow (main branch)

---

// branch a push kore then tag name dia add kora

`git tag <tag_name>` tag add kora new version er jonno zip file dibe
`git push origin <tag_name>` tag a push kora
`git push --delete origin <tag_name>` tag delete kora

---

git reset syntax, usage, and modes

- git reset --mixed: The default option for git reset. Updates the current branch tip to the specified commit and unstages any changes by moving them from the staging area back to the working tree.

- git reset --soft: Known as a soft reset, this updates the current branch tip to the specified commit and makes no other changes.

- git reset --hard: Known as a hard reset, this updates the current branch tip to the specified commit, unstages any changes, and also deletes any changes from the working directory.

// Git commit delete push korar por

`git reset --hard 32c2d09`

// HEAD is now at 32c2d09 Change 1

`git status`
On branch master
nothing to commit, working tree clean

`git log --oneline`

<!--
32c2d09 (HEAD -> master) Change 1
38e2a6e Initial commit
-->

---

`git reset --hard HEAD~1`

// git a kono commit push kore pre delete kora.
HEAD~1 dile last one ta delete hobe and HEAD~2 Dile last 2ta delete hobe. same HEAD~6 dile last 6 ta delete hobe

---

`git log`

// Check old git commit a gache ki na check kora.

---

`git push -f`

// Jodi target commit a gale git a porsh kora lagbe

---
