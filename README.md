# git-master-task
<h3>What is Version Control?</h3>
console.log("Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. ")

<h3>Explain difference between git and github</h3>
<h4>Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories</h4>

<h3>List 3 other github alternatives?</h3>
<h4>Gitlab,     bitbucket,   codeberg</h4>

<h3>Explain the difference between git fetch and git pull</h3>
<h4>The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both</h4>



<h3>Explain in simple terms git rebase and the command for it?</h3>
<h4>Git rebase takes the commits from one branch (let’s call it the “source” branch) and reapplies them on top of another branch (let’s call it the “destination” branch). This process allows developers to fix conflicts, squash commits, and reorder the commit history before merging the source branch into the destination branch.
Now the command;
git rebase master feature</h4>



<h3>Explain in simple terms git cherry-pick and the command for it?</h3>
<h4>Git cherry-pick is a command used in the Git version control system to apply a single commit’s changes to the current branch. This command is helpful when you want to incorporate specific changes from a particular commit into your working branch without merging the entire history of the source branch.
Now the command;
git cherry-pick [commit]</h4>