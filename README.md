#Learn Git

# Branch Feature/Register


```
git co develop
git co -b Feature/Register

```
## Working . . . 

```
git add .
git commit -m "Add Feature Register "
git status
git push origin Feature/Register

```
## Merge โดย จัดการ Pull Request โดย Merge จาก Feature/Register ไปยัง Develop

```
git co develop
git pull
cat README.md
```


# Branch Release/v1.0

```
git co develop
git co -b Release/v1.0 
```
## Working . . .


```
git add .
git commit -m "Working For Release Version1.0"
git status
git push origin Release/v1.0  

```
## Merge โดย จัดการ Pull Request โดย Merge จาก Release/v1.0 ไปยัง Develop และ Master

```
git co develop
git pull
cat README.md
git co master
git pull
cat README.md
```

# HotFix

```
git co -b Hotfix

```
## Working ....

```
git add .
git commit -m "Fix Bug"
git status
git push origin Hotfix
```

## Merge โดย จัดการ Pull Request โดย Merge จาก Hotfix ไปยัง Develop และ Master

```
git co develop
git pull
cat README.md
git co master
git pull
cat README.md
```

