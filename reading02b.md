 # what is Git? #
Git is an Open Source Distributed Version Control System.
Control System: This basically means that Git is a content tracker.
 So Git can be used to store content — it is mostly used to store code due to the other features it provides.
Version Control System: The code which is stored in Git keeps changing as more code is added. Also, many developers can add code in parallel.
 So Version Control System helps in handling this by maintaining a history of what changes have happened.
  Also, Git provides features like branches and merges, which I will be covering later.
Distributed Version Control System: Git has a remote repository which is stored in a server and a local repository which is stored in the computer of each developer.
 This means that the code is not just stored in a central server, but the full copy of the code is present in all the developers’ computers.
  Git is a Distributed Version Control System since the code is present in every developer’s computer.
## Create your local Git repository ##
In your computer, create a folder for your project. Let’s call the project folder `simple-git-demo.`

Go into your project folder and add a local Git repository to the project using the following commands:

`cd simple-git-demo`

`git init`
The git init command adds a local Git repository to the project.

![Wireframe](https://i.stack.imgur.com/F2H1Q.png)


### to add another file and push it to the remote repository. Issue the command: ###

`touch LICENSE`

Add the file to the staging area with the command:

`git add .`

Issue a new commit with the command:

`git commit -m "added license file"`

Push the changes to the master branch of the GitHub repository with the command:

`git push`

When you run this command, you'll be asked for your GitHub username, followed by your GitHub user password. Upon successful authentication, your local repository will be connected to the remote GitHub repository and the readme.txt file pushed to the remote.
