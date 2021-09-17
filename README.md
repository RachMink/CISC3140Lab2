# exploring the use of SVN
SVN vs git


| git Command  | Description| svn Command |
| ------------- | ------------- | ------------- |
| `git init`  | creates new repository |`svnadmin create`|
| `git status`|shows status of changes|`svn status`|
| `git add` | adds changes to the working copy|`svn add`|
| `git commit`| commits changes to the repository <br /> (be sure to use `-m 'message'` to include notes about the commit) |`svn commit`|
| `git clone` | copies a repository <br /> (when using svn this must be done)|`svn checkout`|
| `git log` | prints chronological history of commits and changes|`svn log`|
| `git push` | changes will be submitted to the remote repository <br /> (svn just commits- there is no remote repo) |`svn commit`|
| `git pull`  | update local repository |`svn update`|
| `git branch`  | creates new branch in repository |`svn copy`|
| `git help` | prints the basic commands |`svn help`|
