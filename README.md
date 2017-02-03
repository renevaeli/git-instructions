# git-instructions

PUSH, Starting from the computer (project is in works on PC):
	0. Open git bash

	1. pwd
		find out where you are

	2. cd Desktop/ITK/<project folder>
		opens the folder in the cmd

	3. git init
		creates the git folder

	4. git add .

	5. git commit -m "commit message"
		if you typed git commit you get the weird screen "please enter the commit message..."
		on the first line enter "commit message"
		*******press ESC and then type :wq and hit Enter)********

	6. Go to github.com, create repository, get the url <remotename>

	7. Make .gitignore
		In top folder of project, create new file
		Name the file ".gitignore
		In the file, write the names of the folders and files you want left out, with slash: .idea/

	6. git push <remotename> master 


CLONE, Starting from the a project in Github:
	0. Open git bash

	1. pwd
		find out where you are

	2. cd Desktop
		or whereever you want to copy the folder

	3. Go to github.com, open the repository, get the url <remotename>

	4. git clone <remotename>

	IF THE PROJECT IS ALREADY AN INTELLIJ PROJECT:
		5. "Open" in intelliJ, everything should work

	IF THE PROJECT IS NOT INTELLIJ FORMATTTED:
		5. "Import project", accept the terms - sdk, jdk, ...
		5.1 !!!RIGHT CLICK ON THE MAIN METHOD!!!, run Run ´Main.main()´ - this complies the thing and tells him where main is
		
	PUSH it back to Github:
	6. git add .

	7. git commit -m "commit message"

	8. git push <remotename> master	
		write the url, dont paste it, otherwise automatically submits

PULL, Starting from the project in Github
	0. - 3. you know
	
	4. git pull <remotename> master

	5. Open in IntelliJ, you have the settings already
		modify

	6. git add .

	7. git commit -m "commit message"

	8. git push <remotename> master

	
	
		
