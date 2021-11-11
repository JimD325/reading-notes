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
1.	Add files (git add ________)
2.	Commit “insert message here” 
3.	Push (takes whole version on your machine to the GH) 
This whole Process is Called ACP	
You can add and commit as many files as you would like before you push. 
Git push origin main: Memorize this, its how you push stuff to github. 


