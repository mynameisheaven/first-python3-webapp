1.	Target
	Create a Blog Website

2.	Project Name
	first-python3-webapp

3.	Project Plan
	Schedule -> 16 Days

	Day 1	: setup env
				(1) python --version
				(2) third party lib
					1) pip3 install aiohttp
					2) pip3 install jinja2
					3) pip3 install aiomysql



4.	GIT Command
	(1) create a new repository -> git init
	(2) checkout a repository	-> git clone https://github.com/xxx/xxx.git
	(3)	add and commit			-> git add * / git commit -m "Commit Message"	
	(4)	pushing changes			-> git remote add origin git@github.com:xxx/xxx.git 
								-> git push -u origin master
	(5) branching				-> git checkout -b feature_x
								-> git checkout master
								-> git branch -d feature_x
								-> git push origin <branch>
	(6) Update & Merge			-> git pull
								-> git merge <branch>
								-> git add <filename> if there is conflicts
								-> git diff <source branch> <target branch>
	(7) Tagging					-> git tag 1.0.0 1b2e1d63ff  
	(8) Logging					-> git log --author=mark
								-> git log --pretty=oneline
								-> git log --graph --oneline --decorate -all
								-> git log --name-status
								-> git log --help
	(9) replace local changes	-> git checkout --<file name>
								-> git fetch origin
								-> git reset --hard origin/master
	(10) useful hints			-> gitk (gui)
								-> git config color.ui true
								-> git add -i (interactive)

