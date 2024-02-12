## **Quiz 1**
#### *2/12/2024*
2. .md means "Mark Down", we use this so we can create README files in the Markdown language which is well-known and easy to use.  
3. No  
4. Yes, all projects get a .git  
5. a .git folder will store the edit history of that new project. 
6. cd takes you to a specific folder location
7. ls -a shows you all of the files and folders in a certain location including hidden ones.  
8. pwd shows the exact file location you currently are.  
9. working area, staging area, .git directory  
10. A VCS is a system that allows files to be accessed online and edited offline then reuploaded and allows for multiple branches to be created.  
11. Distributed VCS allows anyone to get access, safe storage, clear organization, 
12. Local VCS, Central VCS, and Distributed VCS
13. Git is the program that allows the connection between GitHub and computers, whereas GitHub is the online storage.  
14. git status tells the upload and commit status of a repository.  
15. git push --all pushes all commits and deletes into GitHub
16. git pull allows for repositories to be grabbed from GitHub and cloned from there to be edited locally.  
17. Markdown is the language in which README files are written in to appear in a specific way.  
18. boldface in Markdown is done with ** on either side of text. (**bold text**)  
19. italic in Markdown is done with * on either side of text. (*italic text*)  
20. git init
21. . and .. allow a pathway to take you a step forward or backward respectively.  
22.
Macke@Macs_Mac MINGW64 ~/git (master)  
$ pwd  
/c/Users/Macke/git  
  
Macke@Macs_Mac MINGW64 ~/git (master)  
$ mkdir testdir/  
22. 6. no this is not a directory as an empty folder can not be tracked, the ls -a shows that this folder is empty.   
22. 7. you would have to use git add --all to add the new directory, git commit, and git push to add it to GitHub to make it a git repository  
22. 8. vim allows files to be created and edited, you must hit escape and then type :wq to write and quit the vim sofware.  
22. 9.  
$ cat README.md   
This is a README.md file for the test git project of quiz1.  
22. 10.  
$ git status  
On branch master  
  
No commits yet  
  
Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
        ../IDS2024S/  
        ./   
        ../testproject/  
  
nothing added to commit but untracked files present (use "git add" to track)  
22. 11.  
$ git add --all  
warning: adding embedded git repository: IDS2024S  
hint: You've added another git repository inside your current repository.  
hint: Clones of the outer repository will not contain the contents of the embedded repository and will not know how to obtain it.  
hint: If you meant to add a submodule, use:  
hint:  
hint:   git submodule add <url> IDS2024S  
hint:  
hint: If you added this path by mistake, you can remove it from the index with:  
hint:  
hint:   git rm --cached IDS2024S  
hint:  
hint: See "git help submodule" for more information.  
warning: in the working copy of 'testdir/README.md', LF will be replaced by CRLF the next time Git touches it adding embedded git repository: testproject  
  
Macke@Macs_Mac MINGW64 ~/git/testdir (master)  
$ git commit -m"testdir"  
[master (root-commit) cd603f6] testdir  
 3 files changed, 3 insertions(+)  
 create mode 160000 IDS2024S  
 create mode 100644 testdir/README.md  
 create mode 160000 testproject  
22. 12.   
$ git status  
On branch master  
nothing to commit, working tree clean  
22. 13. This command force removed(-rf) the testdir that we created and changed the directory back to the home directory. 


 
23. A relative path is one that uses . or .. to move the user forward or backward within a repository and is more appropriate for our projects because if the code is uploaded or used somewhere else it will continue to work. An absolute file path is one that gives the exact names and locations of a file or a direct link and would not work if uploaded somewhere else.  
24. git help -a  
