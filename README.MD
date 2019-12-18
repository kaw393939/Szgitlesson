# Introduction to GIT

1.  GIT is Source Code Managment (SCM)
2.  GIT has a .git folder that stores the versions of the software like a database
3.  A repository is the organinizational unit of a program or software library and you can combine git repository (repo) into larger project.  Repositories are use also the org unit of code that is tested.

4.  Think of GIT like a tree and that branches are copies of the tree.  The git repo has a trunk that we call "Master" and that the branches are copies of the source in various states of completion.  

5. Master is generally considered the production release / version of the software.  You need to create a branch called development that is the working copy of the software that is currently being developed.  Master is the copy that your users use and development is the copy that your developer use.

6.  GIT has a dance called "GIT Flow": 
	Step 0: make sure you have a git repo made or cloned
        Step 1: When you go to work on a feature, bug or task make a branch
        Step 2: Each working piece of code and/or test or action should have a commit tagged with Fix, Feauture, or Task depending on what your doing.  Also, when you have project management system, you should include the ticket number in the commit so that the commit can tracked to the original request from the project manager / project management system.
	Step 3: When your code is done, you need to merge development or master into your branch and check that your program still works.  If it works then you should push it to github / central repo.  Then someone (could you) will make a pull request (like raising your hand when your done) and then the branch you created in step 1 will be merged into usually the development branch, unless your merging the development branch into master to send the softare to the end users.


