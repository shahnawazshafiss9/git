## test only

```javascript
	<Directory /var/www/>  
	Options Indexes FollowSymLinks  
	AllowOverride All  
	Require all granted  
	</Directory>
```

First remove
rm -rf .git*
----------------
1. git init
2. git remote add origin https://***@bitbucket.org/sha9/project.git
3. git add .
4. git status
5. git commit -m "first commit"
6. git config --global user.email "shah@gmail.com"
7. git config --global user.name
8. git commit -m "first commit"
9. git push
10. git push --set-upstream origin master
11 . git status
12. git remote show origin
13. git log
14. git branch
	
	Create new branch
15. git checkout -b new-feature
16. git branch
Add something coding
17. git master
18 git merge new-feature
19. git branch -D new-feature
20. git branch
	Again create new branch
21. git checkout -b new-feature
	Changes in files somehing
22. git add.
23. git commit -m "add goodbye"
24. git master
	Changes somethings in files
25. git add.
26. git commit -m "added aby"
27. git merge new-feture
	If confilect to branch delete one
28. git add.
29.git commit -m "merge resolve"

	

**If change of files to add command  git add.
** git commit -m "save again"


If I want to see previous changes
**git checkout git ID
This command remove current changes.

If change current commit 
**git master 

If want to last commit ID change
**git reset --hard git ID

If want to revered
*git checkout --.

if want to fetch remote branch

**git fetch && git checkout branch_name
