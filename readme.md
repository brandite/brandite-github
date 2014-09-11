# Pre-workshop steps
* Install git on your computer: [Git Downloads](http://git-scm.com/downloads)
* Create a free account on www.github.com
* Email me (pitosalas@brandeis.edu) your user name
* Clone this [Brandeis-demo](https://github.com/pitosalas/brandeis-demo) repository to your computer
* Create a play repository on github: [Set up Git](https://help.github.com/articles/set-up-git), and clone it to your computer also

#### Key concepts
* Repository: All the files, history, modifications, etc. of a single project. Stored either in a folder on your computer or as a unit on Github. Most importantly, it contains all the Commits (or commit objects). Also known as a repo.
* Commit: Used as a noun. A set of files corresponding to the state of the project, all it's files, at a certain point in time. Analogous to a zip or archive of a directory. All commits (except the first one) have a (or more) parent(s), from which they came.

#### Small demo
* Create a simple repo

```
mkdir [project]
cd [project]
git init
```

#### Create a commit
* Tell git what files to include, using `git add`
* Tell git to create the commit, using `git commit`
* The new commit is a 'child' of the previous commit

#### Working with Github
* Just another git repo, "in the cloud"
* Totally separate from the one on your computer
* Use "git push", "git clone", "git pull" to send updates from one copy of your repo to another.

#### Some useful links
* [A Github Tutorial](http://www.sbf5.com/~cduan/technical/git/)

