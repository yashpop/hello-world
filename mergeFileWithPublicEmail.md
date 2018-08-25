We can merge files with the new public email id given by Git using following. 
git -i helps to retain the our original email id inplace and appends the new one

git config --global user.email "32606340+yashpop@users.noreply.github.com"

git rebase -i

git commit --amend --reset-author

git rebase --continue

git push
