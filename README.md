# play Git  
## git commit
- `git commit --amend --date="Sat May 13 15:30 2017 +0800"`  
The commit date will change. 

## git log  
- `git log --oneline --decorate --graph --all`   
Print out the history of commits, showing where your branch pointers are and how your history has diverged.  
```
* c2b9e (HEAD, master) made other changes
| * 87ab2 (testing) made a change
|/
* f30ab add feature #32 - ability to add new formats to the
* 34ac2 fixed bug #1328 - stack overflow under certain conditions
* 98ca9 initial commit of my project
```
ref: https://git-scm.com/book/en/v2/  
