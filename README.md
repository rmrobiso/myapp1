#MyApp

This is just a sample app deploying from vscode git into github repository

 1. Basic Command

	> git init 		// Initialize Local GIT Repository

	> git add <file>	// Add file to index

	> git status		// Check Status of working tree

	> git commit		// Commit changes in Index
	
	> git push		// Push to Remote Repository
	> git pull		// Pull latest from Remote repository
	> git clone		// Clone repository into new directory

 2. Installing GIT
	
	Linux (Debian)
	$ sudo apt-get install git

	Linux (Fedora)
	$ sudo yum install git

	Mac
	http://git-scm.com/download/mac

	Windows
	http://git-scm.com/download/win


 3. Create Project to version
	
	> git init
	
	
 4.  git configuration for name and email

		> git config --global user.name ['name']

		> git config --global user.email ['email']


 5. 	
    > git status
	  > git add .   |  git add index.html

	      - to remove file from state ( unstage command )

		      > git rm --cached index.html

	        > git add *.html  | git add .

	  > git commit -m 'Initial project commit'


 6.  Create the git ignore file

	> touch .gitignore
	--------------------------------
	log.txt
	/dir2
	*.txt
	--------------------------------


 7. Branches

	- create the new branch :
	
	  > git branch mybranch

	  > git checkout mybranch


	- after modifying or adding items : git add and git commit

	- switch to master branch

		> git checkout master

	- merge the changes from mybranch

		> git merge mybranch
		

 8. Remote Repository  [ Github ]

	--------------------------------------------------
	Quick setup — if you’ve done this kind of thing before

	Get started by creating a new file or uploading an existing file. 
	We recommend every repository include a README, LICENSE, and .gitignore.


	…or create a new repository on the command line

		echo "# myapp1" >> README.md
		git init
		git add README.md
		git commit -m "first commit"
		git remote add origin https://github.com/myapp1.git
		git push -u origin master
                

	…or push an existing repository from the command line

		git remote add origin https://github.com/myapp1.git
		git push -u origin master

	…or import code from another repository

		You can initialize this repository with code from a 
		Subversion, Mercurial, or TFS project.
	--------------------------------------------------


 9.
	> git remote
		- none
	> git remote add origin https://github.com/myapp1.git

	> git remote
		- origin

	> git push -u origin master


    Back to github.com

	    - referesh the browser
	
	  create the README.md

		  > touch README.md

	  > git add .

	  > git commit -m 'Created the README file'


