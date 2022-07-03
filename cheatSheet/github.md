to add a repository, make a repo on github.com
git clone HTTPsAddress

see weather the repo is commit able or no
git status

to make locale repo staged
git add .           stage all the changes.
git add name.file       only stage specific file.

to commit git
git commit -m "commit title"
git commit -m "commit title" -m "commit description"
git commit -am "commit title"       only works with modified files and doesn't need git staging.
git log     to see all commits

see the file modification
git diff

pushing to github
git push -u origin master
git push        from next time after using above command.

make a local repo, and go live to github
make a local folder
git inti        to initiate git
make a github repo with a same name as local folder
git remote add origin HTTPsAddress
git push -u origin master
git push

undoing git staging
git reset name.file
or
git reset HEAD~1        to reset one last commit
git reset .         to reset all the staged changes
git reset commitNumber         to undo commit without changing codes.
git reset --hard commitNumber           undoing as well as erasing the code till the selecting commit.

downloading github codes
git pull        to download changes from live repo to local repo.
git fetch       to download a different branch and code change.
git fetch --all


create a file
echo "# foldername" name.file

branch
git branch      to see the available branches
git checkout -b branchName      to make a new branch
git checkout branchName     to switch to a branch

pushing branch
git push --set-upstream origin branchName       to push the new branch
or
git push -u origin branchName

merging
git diff branchName         to see changes in branch
git merge main

deleting brach
git branch -d branchName

to avoid merge conflicts
delete the line from vs code and commit