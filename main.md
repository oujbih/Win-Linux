## Adding an existing project to GitHub using the command line 
```
git init
git config user.name "oujbih"
git config user.email "abderahimoujbih@gamil.com"
git add .
git commit -m "let's begin the journey"
git remote add origin https://github.com/oujbih/hackthebox.git
#git remote set-url origin git@github.com:oujbih/hackthebox.git
git push -f origin master
```
## ssh github
```
ssh-keygen -t rsa -b 4096 -C "abderahimoujbih@gmail.com" 
eval "$(ssh-agent -s)"
```
