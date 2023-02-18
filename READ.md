* Installed CLI tools <xcode-select --install>
* Installed gh <brew instal gh>
* Created a directory LocalDemoProject in home <mkdir LocalDemoProject>
* Created a file READ.md <touch READ.md>
* Initialize git <git init> (it creates the .git directory)
* Adding READ.md to staging area <git add READ.md>
* Commit <git commit -m “Initial Commit”>
* Creating a branch “develop” <git branch develop> (Git requires that you have at least one commit in your repository before you can create a new branch.)
* Switch to branch develop <git checkout develop>
* Created a new branch in develop called “Feature_1” <git branch Feature_1>
* Switch to branch Feature_1 <git checkout Feature_1>
* Created a text file feature1.v.1.txt <vim feature1.v.1.txt>
* Added the file feature1.v.1.txt to staging area <git add feature1.v.1.txt>
* Commit <commit -m "First commit for Faeture_1.”>
* In the home directory login to GitHub account <gh auth login>
	? You're already logged into github.com. Do you want to 					reauthenticate? Yes
	? What is your preferred protocol for Git operations? SSH
	? Upload your SSH public key to your GitHub account? Skip
	? How would you like to authenticate GitHub CLI? Login with a web 			browser

	! First copy your one-time code: BA1B-122D
	Press Enter to open github.com in your browser...
	✓ Authentication complete.
	- gh config set -h github.com git_protocol ssh
	✓ Configured git protocol
	✓ Logged in as nehamagarde
* Created a new repository <gh repo create LocalDemoProject --public>
* Push the changes to repository to the master branch of the repo <git push -u origin master>
* git push --set-upstream origin Feature_1
* git push --set-upstream origin develop
