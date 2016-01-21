# How_to_use_github
Git: Why 'Everything up-to-date' when pushing?
Why does Git refuse to push, saying “everything up to date”?
git push with no additional arguments only pushes branches that exist in the remote already. 
If the remote repository is empty, nothing will be pushed. 
In this case, explicitly specify a branch to push, e.g. git push master
answer:commit,then push origin master.
example as:
git commit -m 'my images'
git push origin master
