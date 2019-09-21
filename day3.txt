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

