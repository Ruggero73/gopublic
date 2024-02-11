## …or create a new repository on the command line
```
echo "# gopublic" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ruggero73/gopublic.git
git push -u origin main
```


## …or push an existing repository from the command line
```
git remote add origin https://github.com/Ruggero73/gopublic.git
git branch -M main
git push -u origin main
```

## Access denied error 403
```
git remote set-url origin https://<token>@github.com/<username>/<repo>
git remote set-url origin https://<token>@github.com/Ruggero73/gopublic.git
```
## Page URL
```
https://ruggero73.github.io/gopublic/
```