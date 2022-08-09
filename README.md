# learning-k8
Learning kubernetes

# 1. Initialize local git repo
cd <Project Folder>
git init

# 2. Create new repo in Github with same Project folder name

# 3. Point local git to newly created remote Github repo 
git remote add origin https://github.com/<github id>/<Project Folder>.git
git fetch

# Create and switch local branch pointing to remote branch in github
git switch -c main origin/main
git pull


