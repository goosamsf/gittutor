#### Git Practice

---

1. In your shell, add your user name.  
    `git config --global user.name "your_username"`  

2. Add your email address:  
    `git config --global user.email "your_email@address.com"`  

3. To check the configuration, run :  
    `git config --global --list`

---

## When you open a repository in Github
```
echo "# contents" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/goosamsf/repo_name.git
git push -u origin main

```
