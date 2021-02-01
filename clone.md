# Clone

## Definition

* Allows users to obtain a local development clone of an already existing central repository [1]
* How to clone a repository:
	* “git clone”
	* Used to create a copy or clone of remote repositories [1]
	* Must pass a repository URL, and supports a few different URL formats (HTTPS, SSH, GitHub CLI) [1]
	* Creates a remote connection called “origin” which points back to the original repository [2]

## Examples 
Here **git clone** is being used to clone the repository "Project1-IS601-Spring-2021" using HTTPS
<img src="./git_clone/git_clone.jpg" width="500" height="300">

Changing the directory to the cloned repository "Project1-IS601-Spring-2021", and checking to see if the files were cloned successfully
<img src="./git_clone/git_clone_2.jpg" width="500" height="300">

Seeing that "Project1-IS601-Spring-2021" on GitHub matches the files that were cloned
<img src="./git_clone/git_clone_3.jpg" width="500" height="300">

Creating a basic markdown file, git.md, and checking its status using **git status**
<img src="./git_clone/git_clone_4.jpg" width="500" height="300">

Adding the file, git.md, to the staging area, and then commiting the changes.
<img src="./git_clone/git_clone_5.jpg" width="500" height="300">

Pushing the changes from origin to main
<img src="./git_clone/git_clone_6.jpg" width="500" height="300">

Checking to see that the file was pushed successfully. In this case, it was a success
<img src="./git_clone/git_clone_7.jpg" width="500" height="300">

Sources:

* [Setting up a repository](https://www.atlassian.com/git/tutorials/setting-up-a-repository) 
* [git clone](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone)

[Link to Previous Page](/terms.md)