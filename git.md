1.Explain what git is and its purpose?
A.   Git is a version control system for software development its purpose is to tack changes in
source code and coordinate work between multiple developers Git allows developers to keep a history 
of their work rvert to previous versions and collaborate on the same codebase This helps to ensure that 
the code remains organized and stable even as multiple developers work on it simultaneously

2.How to create a new repository in Git?
  1. Go to Github and log in to your account 
  2. click on the "+" sign in the top right corner then select "New Repository"
  3. Fill in the repository name description and choose the visibility (public/private)
  4. cick on the "create repository" button 
  5. if you want to add files to the repository you can do so by clicking on the "upload files"
  button and dragging the files into the browser window or by using the command line
  a. git clone https://github.com/<username>/<repository>.git
  b. cd <repository>
  c. touch README.md
  d. git commit -m "Add README"
  e. git push origin master
    These steps will create a new repository on GitHub and add new file called "README.md" to
    it 

    3.Explain the difference between Git pull and Git Fetch?
    A.  git pull and git fetch are both Git commands that allow you tu download updates from a
    remote repository However they differ in their behaviour and the changes they bring into your loacal 
    repository 
       git pull is a combination of git fetch and git merge it downloads the latest changes from the 
       remote repository and automatically merges them into your current branch instead it stores the 
       changes in a remote branch which you can inspect and merge manually later This allows you to 
       review the changes before integrating them into your local repository which can be useful if
       you want to ensure that the changes ar compitable with your current work
     
       In summary `git pull` is a convinent way to quickly merge the latset changes fro the remote
       repository into your local repository while `git fetch`
       gives you more control over the integration process

    Expain difference between git clone and git fork?
    A.  `git clone` and `git fork` are both git commands but they serve different purpose
        `git clone` is used to create a loacal copy of a remote repository this allows you to download
        the entire repository including all machine you can then make changes to the local repository 
        inculding all of its files and history onto your local machine you can then make canges to the 
        local repository and push them back to the remote repository
        `git fork` on the other hand, is a feature of hosting services like GitHub and GitLab it 
        allows you to create a copy of a remote repository under your own account withot having clone
        the repository to your local machine  this makes it easy to contribute to a project without 
        having to worry about setting up a development environment once you have forked a repository
        you can clone it to your local machine and start making changes

        In summary `git clone` is used to create a local copy of a remote repository while `git fork`
        is used to create a remote copy of a repository under your own account.







