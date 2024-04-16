# GitCommands (using cmder)
How to check git version : git --version

//Configuring git account locally on your computer
To configure username : git config --global user.name yourname
To configure email : git config --global user.email typeemail

//To check git account username and email
To check username : git config user.name
To check email : git config user.email

// Accessing and managing files and directories using cmder
How to enter into a child directory/folder : cd foldername
How to leave a child directory/folder : cd..
How to create a directory/folder : mkdir foldername
How to delete a directory : rmdir foldername
How to create a file in a directory : touch filename
How to delete a file in a directory : rmdir filename
How to check the list of items in current directory : ls

//Repositories(Repo's) 
A repo is a container that houses the project you want to track with Git.
//creating Repositories
How to initialize git on a folder/creating a Repository : git init

//Staging files
How to add files to staging area : git add filename 
How to add files all files to the staging area : git add .
How to check files added to the staging area : git status
How to remove files from the staging area : git rm --cached filename

//Making Commits
A commit is a save point of our code at that particular instance.
How to commit our code : git commit -m "# type commit title here"
How to check our commits : git log
How to check a summarized version of all commits available : git log --oneline
How to checkout a commit : git checkout #commitID
How to return to the master branch after checkout : git checkout master

//Branches
How to create a new branch : git branch branchname
To checkout a branch : git checkout branchname
To return to master branch : git checkout master
How to check list of the branches in a repo : git branch -a
How to delete a branch : git branch -D branchname




