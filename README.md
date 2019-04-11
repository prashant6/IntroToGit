# IntroToGit

<p>Things I learned in git </p>

1. cloning a repository   <br>
	git clone URL
2. adding/removing a file to stage area <br>
	git add "file-name"
   <br>git reset HEAD "filename"  (for unstaging file)
3. commiting changes <br>
	git commit -m "message"  
4. pushing changes to remote repo <br>
	git push "origin repo-name ( optional)" 
	<br>*git push -u origin "branch-name"* ( it helps in tracking and pulling from branches )
5. pulling changes from remote repository <br>
	git pull <br>
6. seeing the log 
	git log "--pretty=oneline(optional)" <br>
7. creating a branch <br>
	git branch "branch-name"<br>
8. switching to another branch ( git checkout branch-name)
9. merging branch-A into branch-B <br>
	git merge branch-A (currently we are in branch-B )<br>
10. deleting a branch <br>
	git branch -d "branch-name" ( it will delete locally ) <br>
	git push origin --delete "branch-name" ( it will delete from remote site)
11. git help "command-name"
12. forking a repo
13. seeing the status 
	git status 
14. .gitignore file ( to hide critical information)
15. creating a folder inside a repo ( simply make a folder and create a .gitignore file in it and push )
16. git init 
17. to display current head position (cat .git/HEAD)
18. To undo changes
18. i) before committing <br>
		git checkout -- file-name <br>
		git checkout -- . (for changes in all files)
  
   ii) after committing any one (a) or (b) or (c)
   		
   		(a)	git checkout commit-id (read only)
   		
   		(b)	git revert commit-id (if merge conflicts occur) then solve the conflict and ,
   			git add file-name ....then 
   			git revert --continue || git revert --abort || git commit -m "message"

   		(c) git reset --soft||mixed||hard commit-id
   	iii) after pushing the commits 
   		git revert commit-id-from..commit-id-to
   		git push
<p>master branch</p>

<p>merged feat branch into master</p>

* Few good practices

i) always pull changes before merging into a branch

https://www.google.co.in

[Google](https://www.google.com)

[Facebook](https://www.facebook.com/people/Prashant-Singh/100001252526853)
