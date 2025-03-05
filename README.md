# Git commit steps

#### 01. Initialise git repository inside your root folder.
```bash
git init
```

#### 02. You have to write to add all files ready for git commit.
```bash
git add .
```

#### 03. You do have to commit it by writing the command.
```bash
git commit -m "initial commit"
```
#### 04. Then you have to add remote what you have copied.
```bash
git remote add origin https://github.com/Vraj4112/test-bloggingapp.git
```

#### 05. Then make initial push.
```bash
git push origin master
```

### …or create a new repository on the command line
```bash
- echo "# test923" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/Vraj4112/test923.git
- git push -u origin main
```

### …or push an existing repository from the command line
```bash
- git remote add origin https://github.com/Vraj4112/test923.git
- git branch -M main
- git push -u origin main
```
### …Create initial local repo commit to get original code back
```bash
- npm init
- npm add .
- git branch -M main
- git commit -m "first commit"
```
- so if you want revert back local changes it will be easy to get that back
