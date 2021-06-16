Step 1:
git repo need to be created in github
step 2:
add some file in that repo and commit them 

commands :
[
git status: to check the status
git add . : this will add all the files to commit
git commit -m "added my my files": this will comit our changes
git push: this will push our changes to git repo

]

step 3:
add new directory name it submodule
commands
[
mkdir submodule
cd submodule
git init: this will Initialized empty Git repository into submodule
]
step 4:
repeat step 2

step 5:
now check in submodules into git repo
command
[
git submodule add ./Submodule
]