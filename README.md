# IntroToGit

<p>Things I learned in git </p>

1. cloning a repository   
		(a) git clone URL
2. adding/removing a file to stage area ( git add "file-name" )
   <br>git reset HEAD "filename"
3. commiting changes ( git commit -m "message" ) 
4. pushing changes to remote repo ( git push "origin repo-name ( optional)" )
	<br>*git push -u origin "branch-name"* ( it helps in tracking and pulling from branches )
5. pulling changes from remote repository ( git pull )
6. seeing the log ( git log "--pretty=oneline(optional)" )
7. creating a branch ( git branch "branch-name") 
8. switching to another branch ( git checkout branch-name)
9. merging branch-A into branch-B ( git merge branch-A "currently we are in branch-B ")
10. deleting a branch 
	10 i) git branch -d "branch-name" ( it will delete locally ) <br>
	10 ii) git push origin --delete "branch-name" ( it will delete from remote site)
11. git help "command-name"
12. forking a repo
13. seeing the status ( git status )
14. .gitignore file ( to hide critical information)
15. creating a folder inside a repo ( simply make a folder and create a .gitignore file in it and push )
16. git init 
17. to display current head position (cat .git/HEAD)
18. To undo changes
19. i) before committing <br>
		git checkout -- file-name <br>
		git checkout -- . (for changes in all files)
  
   ii) after committing either (a) or (b)<br>
   		
   		(a)	git checkout commit-id (read only) <br>
   		
   		(b)	git revert commit-id (if merge conflicts occur) then solve the conflict and ,<br>
   			git add file-name ....then <br>
   			git revert --continue || git revert --abort || git commit -m "message"
<p>master branch</p>

<p>merged feat branch into master</p>

* Few good practices

i) always pull changes before merging into a branch

https://www.google.co.in

[Google](https://www.google.com)

[Facebook](https://www.facebook.com/people/Prashant-Singh/100001252526853)
