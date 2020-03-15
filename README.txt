482 project 

Authors:
Jon Spiwak 
Andreas Frame

git commands:

push:
https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line
$ git add .
$ git commit -m "message"
$ git remote add origin remote repository URL	# Sets the new remote
$ git remote -v		# Verifies the new remote URL
$ git push origin master (optional -f)

pull:
https://help.github.com/en/github/using-git/getting-changes-from-a-remote-repository
$ git pull remotename branchname