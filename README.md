git is a version control system(free and open source)
git is supported by multiple platforms
git focuses on the file content itself
feature branches provide an isolated environment for every change to your codebase. When a dev wants to start working on something they create a new branch ensuring that only production quality code will be merged 
in order for the changes to be tracked they must reach the staging area otherwise they will be ignored
the content of the files, the relationship between files and directories, versions and commits in the git repository are secured with a cryptographically secure hashing algrorythm called SHAI - this protects the code and the change history against accdents and ensures that the history is fully traceable
master - main branch is the production code - never merge something that is not tested or that will cause issues in building the project
to save changes locally in git history make a commit
each commit should have a descriptive clear message
use git push command to make your code from the branch appear on the remote repository
commit as soon as you have a piece of working code
never use force push on master
use branches and suggestive names 
GitHub allows you to resolve merge conflitcs remotely and in general it has a very user friendly interface
GitHub allows collaboration between developers that work on the same project
automatically generates emails for review, access boundaries that you can set up for your project, git commands not only increase performance but also project security and quality of code
conflicts arise when two people work on the same file and have changes the same lines or if one developer deleted a file and another one modified the same file; 