# Day 3 Notes


Raw Word Notes: 

11/10/2021 In Class Notes

Review: 
Sharing Code/Collab, DVCS for the masses. 
What is Git? It is a version control system. So its like being able to look at a piece of code, and know everywhere that piece of code has been. It attaches drafts onto the final version, and allows you to track the changes over time. This is huge for an employer, allows them to see how you have improved over time. Git also allows multiple developers to work on the same code base. You can also view, apply, and remove these changes as time goes on. Also allows you to keep all of your project files in one repository (basically just means the same as directory or folder). 
Snapshots in Time: Every time you make a change, you do what is called a “commit” means this is what you are going to add into the codebase. A commit is every iteration or version of a file. Represents successive version of a file/files. Commits are the Git equivalent of “save as”. Each successive version creates a new snapshot of the file. Git takes snapshots atpoints in time, keeps a history of what those snapshots look like, has a label called HEAD that means you are here, and then you usually give it a message. 
Github: Is a storage location in the cloud that actually stores your code. It is NOT git. Github stores projects that have GIT in the cloud. Use it for version tracking, reviewing changes, keep changes separate until you want to add them in.With git (version control) and Github (online storage) you can have team members work on same file without messing eachother up, keep a history of each file over time, work on code on your own computer and sync it with whats online. 
Repositories/Repos/Projects/Folders
	A repository is a collection of files that ouve told git to pay attention to. One project=one repository
Really large projects might have multiple repositories for diff parts of their system IE front end vs back end. Repositories can live on github and/or your computer. 

Clone Github to Git on computer using command git clont “insert URL here”. Only things with the .git folder is going to be monitored by git. Then we will open it up in VS code, and then were gonna write some code that does not yet exist in the cloud. When you make changes to your machine, GH does not know WTF is going on. Need to do three things to get GH to know about local machine. 
1.	Add files (git add ________) git add . 
2.	Commit “insert message here” git commit -m""
3.	Push (takes whole version on your machine to the GH) git push origin main 

This whole Process is Called ACP	
You can add and commit as many files as you would like before you push. 
Git push origin main: Memorize this, its how you push stuff to github. 

Reading Notes: 

[Reading Link](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1) 

Version Control: allows you to revist previous versions of a file, so if you screw up the code you can just revert back
Local Version Control: One database on your hard disk that stores the changes
Centralized Version Control: Version control set up on a server. Allows many people to work on the same files. 
Distributed Version Control: Same as centralized, except there are backups (mirrored repositories) in case of server failure

What is git? DCVS
any saved version of your project (called a commit). Git creates snapshot and stores references to it. Git relies mostly on local operations, so even if you are not connected to the interwebs you can still work, just cant upload it without a connection. Tracks every change applied to any directory/file. 

3 states of git files 
1. Comitted: data securely stored in a local database.
2. Modified: File has been changed but not comitted to the database. 
3. Staged: Flagged a files changed version to be comitted in the next snapshot. 
 
 Getting (gitting... hehe) Help

Type in git help command
import: 
1. cd test (swith to the target projects directory)
2. git init (git init command, at his stage you have created a new subdirectory named.git thatas the files)

Making a copy= cloning, use command git clone "url goes here"

Workflow: 

![worflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

Working Directory is where the actual files are 
Index is the area used for staging
head points to the most recent commit. 

Life cycle of sa file status: 

![](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

Tracked files are part of the most recent file snapshot, can be modified unmodified or staged.
Untracked files were not in last snapshot, and do not currently reside in the staging area.  