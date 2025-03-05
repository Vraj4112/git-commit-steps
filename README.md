# git-commit-steps

### Steps
#### Step-01 
- initialise git repository inside your root folder by "git init"
#### Step-02
- you have to write "git add ." to add all files ready for git commit
#### Step-03
- then you have to commit it by writing the command "git commit -m "Initial Commit"".
#### Step-04
- then you have to add remote what you have copied for example "git remote add origin https://github.com/Vraj4112/test-bloggingapp.git"
#### Step-05
- then make first push "git push origin master".


### …or create a new repository on the command line
```plaintext
- echo "# test923" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/Vraj4112/test923.git
- git push -u origin main
```

### …or push an existing repository from the command line
```plaintext
- git remote add origin https://github.com/Vraj4112/test923.git
- git branch -M main
- git push -u origin main
```
### create initial local repo commit to get original code back
```plaintext
npm init
npm add .
git branch -M main
git commit -m "first commit"
```
- so if you want revert back local changes it will be easy to get that back
