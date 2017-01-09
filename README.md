1.push local branch modification to remote branch.
--git push origin local_brancName:remote_branchName

2.associate a local branch and linked to remote branch
git init
git add README.md
git commit -m "first commit"
git remote add origin remote url.
git push -u origin master

3.rollback
git reset --hard SHA-1
git push --force

4.git ignore
add file .gitignore -> add ignore file into this file
git rm -r --cached .
git add .
git commit -m "" --this will delete the ignored file in the git repository
git push




