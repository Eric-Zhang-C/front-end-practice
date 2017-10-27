# the introducion of Git Workflow #
by 516030910273 
- - -
- - -
## what ##
Git workflow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly. 
### git & github ###
![git](/pic/git.jpg)
Git : a version control system

GitHub : a web-based Git or version control repository and Internet hosting service (platform)
- - -
- - -
## why ##
 Strong support for non-linear development

 Distributed development

 Efficient handling of large projects

 Cryptographic authentication of history

 Pluggable merge strategies
- - -
- - -
## how ##
### Create a branch ###
![1](/pic/1.png)
where to try out new ideas and don't affect the *master* branch
- - -
### Add commits ###
![2](/pic/2.png)
keeps track of your progress as you work on a feature branch

create a transparent history that others can follow to understand what you've done and why

commit message : a description explaining why a particular change was made
- - -
### Open a Pull Request, discuss and review your code ###
![3](/pic/3.png)
initiating discussion about your commits.

anyone can see exactly what changes would be merged if they accept your request(because they're tightly integrated with the underlying Git repository)
- - -
### Deploy ###
![4](/pic/4.png)
deploy your changes to verify them in production
- - -
### Merge ###
![5](/pic/5.png)
Now changes have been verified in production, it is time to merge code into the master branch.

Once merged, Pull Requests preserve a record of the historical changes to code.
- - -
- - -
