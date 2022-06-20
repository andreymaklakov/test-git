git clone url (if file is on github)

git init (to create .git folder, if create folder localy)
then create repository on github
git remote add origin repositoryURL

ls -a (checkng files in folder)

git config user.name
git config user.email

git status
git add files or git add .
git commit -m "comment"

git log / git log --oneline

git push repositoryUrl branchName
(repositoryUrl - git remote -v)
(branchName - git branch)
git push origin main

git reset fileName(if git add wrong file)

git diff (check what was changed)

git reset --hard(reset all changes after last git commit )

git branch newBranchName (to create new branch)
git checkout BranchName(to change branch)

git pull repositoryUrl branchName(to add changes from github to local file)

git branch -d branchName (to delete branch in local file)

git merge branchName (to transfer code to main branch need to be on main branch and branchName is where is code transfered from(before transfer that branch must be pushed on github))
