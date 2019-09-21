### Version Control
   - VCS: Local Version control systems
        - One database that stores changes to files
	 - CVCS: Cetralized Version Control
        - Collaboration within a team on a single file or set of files
	      - Single server storing all changes and file versions
		    - Can be accessed by different clients
		    - Allows more knowledge of team activities with certain files
		    - Gives administrators more control over the divvying process
	- DVCS: Distributed Version Control Systems
		    - Allows you to create mirrored repos. 
			- A back-up that can easily replace any lost information on a server.
		    - You can create multiple mirrored repos, allowing for multiple people to work on a joint project.

### What is Git?!?! Finally…
1. Snapshots
		- A DVCS that stores data in a file system made up of snapshots
		- Everytime you save/commit a changed version of your project, it creates a snapshot of the file and stores a reference to it
1. Local Operations
		- Git relies on local operations, making it so you can do a project offline.
1. Tracking Changes
1. States of Git
		- Comitted: Data is securely stored in a local database
		- Modified: File has been changed but not committed to the database
    - Staged: Flagged a file's changed version to be committed in the next snapshot

#### A-C-P

|Steps| Command | Effect |
| --- | --- | --- |
| 1 | cd projects | changes you to projects directory |
| 2 | ls -la | shows list of files in projects |
| 3 | git clone "link" | clones web link to file |
| 4 | ls -la | lists files |
| 5 | cd _file_ | _file_ is the file you want to be working in |
| 6 | ls -la | shows list of your master git directory |
| 7 | code . | opens all files into VSCode for edit |
| 8 | git status | lists files that were changed |
| 9 | git add . | adds all changed files to master git file |
| 10 | git commit -m "" | write a commmit message |
| 11 | git push origin master | pushes the file to the cloud |

Learned some pretty cool stuff today!!

I look forward to using all of the tools available!!


[Home](README.md)