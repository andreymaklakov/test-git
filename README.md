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
<<<<<<< HEAD

git branch newBranchName (to create new branch)
git checkout BranchName(to change branch)

git pull repositoryUrl branchName(to add changes from github to local file)
=======
>>>>>>> c427007778c3e68407e219bcf251df1d2ee36d21
