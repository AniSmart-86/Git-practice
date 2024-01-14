# Git-practice Test By Ani Emmanuel
<h2>Explain Version Control</h2>
<h4>What is Version Control?</h4>
<p>Version control - also known as source control or revision control - is an important software development practice for tracking and managing changes made to code and other files. It is closely related to source code management..</p>

<h4>The basics of version control</h4>
<p>With version control, every change made to the code base is tracked. This allows software developers to see the entire history of who changed what at any given time — and roll back from the current version to an earlier version if they need to. It also creates a single source of truth.
<br>
<br>
Version control (or source control or revision control) serves as a safety net to protect the source code from irreparable harm, giving the development team the freedom to experiment without fear of causing damage or creating code conflicts.

If developers code concurrently and create incompatible changes, version control identifies the problem areas so that team members can quickly revert changes to a previous version, compare changes, or identify who committed the problem code through the revision history. With a version control system (VCS), a software team can solve an issue before progressing further into a project. Through code reviews, software teams can analyze earlier versions to understand the changes made to the code over time.

Depending on a team's specific needs and development process, a VCS can be local, centralized, or distributed. A local VCS stores source files within a local system, a centralized VCS stores changes in a single server, and a distributed VCS involves cloning a Git repository.

Version control enables teams to collaborate and streamline development to resolve conflicts and create a centralized location for code.</p>

<h3>Why use version control?</h3>

<p>As organizations accelerate delivery of their software solutions through DevOps, controlling and managing different versions of application artifacts — from code to configuration and from design to deployment — becomes increasingly difficult.

Version control software facilitates coordination, sharing, and collaboration across the entire software development team. It enables teams to work in distributed and asynchronous environments, manage changes and versions of code and artifacts, and resolve merge conflicts and related anomalies.</p>

<h3>What is a version control system?</h3>

<p>A version control system (VCS) tracks changes to a file or set of files over time. The most common type is a centralized VCS, which uses a server to store all the versions of a file. Developers can check out a file from the server, make changes, and check the file back in. The server then stores the new version of the file.</p>

<h3>Types of version control systems</h3>

<p>The two most popular types of version or revision control systems are centralized and distributed. Centralized version control systems store all the files in a central repository, while distributed version control systems store files across multiple repositories. Other less common types include lock-based and optimistic.
<br>
<ol>
<li><b> Distributed<b> 
A distributed version control system (DVCS) allows users to access a repository from multiple locations. DVCSs are often used by developers who need to work on projects from multiple computers or who need to collaborate with other developers remotely.</li>
<br>
<li><b>Centralized</b>
A centralized version control system (CVCS) is a type of VCS where all users are working with the same central repository. This central repository can be located on a server or on a developer's local machine. Centralized version control systems are typically used in software development projects where a team of developers needs to share code and track changes.</li>
<br>
<li><b> Lock-based</b> 
A lock-based version control system uses file locking to manage concurrent access to files and resources. File locking prevents two or more users from making conflicting changes to the same file or resource.</li>
<br>
<li><b>Optimistic</b> 
In an optimistic version control system, every user has their own private workspace. When they want to share their changes with the rest of the team, they submit a request to the server. The server then looks at all the changes and determines which ones can be safely merged together.</li></ol></p>

<h3>Benefits of version control</h3>


<li>
Quality 
Teams can review, comment, and improve each other's code and assets.
</li>
<li>
Acceleration 
Branch code, make changes, and merge commits faster.
</li>
<li>
Visibility 
Understand and spark team collaboration to foster greater release build and release patterns. Better visibility improves everything from project management to code quality.


</li>

<h2>Explain difference between git and github</h2>

<p><b>Git:</b> this is a free, high-quality distributed version control system suitable for tracking modifications in source code in software development. It was originally created as an open-source system for coordinating tasks among programmers, but today it is widely used to track changes in any set of files. The key objectives of Git are as follows:

<li>Speed and efficiency</li>
<li>Data integrity</li>
<li>Support for distributed and non-linear workflows</li></p>


<h4>While</h4>
<p><b>Github:</b> is a web-based Git repository. This hosting service has cloud-based storage. GitHub offers all distributed version control and source code management functionality of Git while adding its own features. It makes it easier to collaborate using Git. 

Additionally, GitHub repositories are open to the public. Developers worldwide can interact and contribute to one another’s code, modify or improve it, making GitHub a networking site for web professionals. The process of interaction and contribution is also called social coding.</p>

<h4>Git and GitHub Operate Completely Differently</h4>
<p>The main Git vs GitHub difference is in their functionality. While they both provide source code management (SCM) and make merging and sharing code easier, this is pretty much where their similarities end. Think of Git as a single computer and GitHub as a network of multiple interconnected computers, all with the same end goal but a wildly different role for how to get there.

At its core, Git is a free, open-source software distributed version control system (DVCS) designed to manage all source code history. It can keep a history of commits, can reverse changes, and lets developers share code. Each developer must have Git installed on his or her local device to collaborate. It is commonly referred to as one of the best DevOps tools to understand and use in the developer space, and it’s among the most widely used tools today. Companies like Amazon, Facebook, and Microsoft use it, to name a few.

GitHub, on the other hand, is a web-based hosting service for Git repositories. It offers all of Git’s DVCS SCM and has some additional features. This includes collaboration functionality like project management, support ticket management, and bug tracking. With GitHub, developers can share their repositories, access other developers’ repositories, and store remote copies of repositories to serve as backups.</p>

<h4>Both Git and GitHub Handle Commands Differently</h4>
<p>Git developers themselves perform a command-line tool where code changes like commit and merge within the Git tool on their own local devices. By contrast, GitHub provides its cloud-based graphical interface where these tasks are performed. The interface also offers developers access control, collaboration features, and various task-management tools.

When it comes to commands, Git focuses exclusively on SCM tasks like push and pull, commit, reset, fetch, and merge. GitHub, meanwhile, serves as a host for Git repository teams to store their code in a centralized location. While Git is a tool that’s used to manage multiple versions of source code edits that are then transferred to files in a Git repository, GitHub serves as a location for uploading copies of a Git repository.

In a sense, then, there’s no comparison when it comes to Git vs. GitHub as far as their function. They complement rather than compete with each other in this space.</p>


<h4>They’re Owned by Different Companies</h4>
<p>Git has remained an open-source tool since it was first released in 2005. To this day, it is maintained by the Linux Foundation as part of the open-source ecosystem of tools and technologies (the Linux founder also created Git). By contrast, GitHub was launched as a company in 2008 and acquired by Microsoft in 2018.</p>

<h4>List 3 other github alternatives</h4>
<p><b>The 3 other github alternatives are:</b>
<li>Bitbucket</li>
<li>Sourceforge</li>
<li>Launchpad</li>
</p>

<h4>Explain the difference between git fetch and git pull</h4>
<p>The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.
<br>
<br>
To really understand the difference between pull and fetch, you must know how a Git installation is structured.
<br>
<br>
On a user’s workstation, a Git installation includes the following items:
<li>The local Git repository where the history of all commits across all branches are maintained.</li>
<li>
A working directory where a developer actively edits and updates files that Git tracks.</li>

<h4>Benefits of the git pull command</h4>
<p>If a developer finds out that there are new, updated files on a remote repository like GitHub, they will likely want to copy those changes from GitHub to both their local repository and into their working directory.<br>
<br>
This is what the git pull command does. The git pull command updates both the user’s local Git repository and the files in their working directory.
<br>

That provides the developer with two benefits:
<ol>
<li>The local Git repo is now in sync with the remote repo.</li>
<li>The local filesystem has the latest, most up to date files.</li>
</ol>
<br>
<br>
The git pull command has one prerequisite: the user cannot be actively editing any tracked files in their local workspace that conflict with what’s on the remote server.
<br>
<br>
If Git notices any conflicting files in the user’s workspace, it aborts the task of updating the user’s workspace and only updates the user’s local Git repo.</p>
<br>
<h4>Benefits of the git fetch command</h4>
<p>If you are actively working on files tracked by Git, but you still want to update your local repository with the latest changes from a remote repository, use the git fetch command.
<br>
<br>
A git fetch updates your local repo with all of the latest changes from a remote repo but doesn’t make any changes to your local workspace.
<br>
<br>
The benefit of the git fetch vs git pull is that a fetch enables you to continue editing files in your local working directory without having to merge your code with updates from the remote repo.
<br>
<br>
With a git fetch, you can finish editing files locally, commit your files and then do a git merge to synchronize your updates with the fetched files. This brings you up to date with the updates the fetch pulled down from the remote machine.</p>
<br>
<br>
<h4>Explain in simple terms git rebase and the command for it</h4>
<p>The git rebase command allows you to easily change a series of commits, modifying the history of your repository. You can reorder, edit, or squash commits together.
<br>
<br>
Typically, you would use git rebase to:
<li>Edit previous commit messages</li>
<li>
Combine multiple commits into one</li>
<li>
Delete or revert commits that are no longer necessary
</li>
<br>
<h4>Rebasing commits against a branch</h4>
<p>To rebase all the commits between another branch and the current branch state, you can enter the following command in your shell (either the command prompt for Windows, or the terminal for Mac and Linux):
<br>
<br>
git rebase --interactive OTHER-BRANCH-NAME
</p>
<br>
<br>

<h4>Rebasing commits against a point in time</h4>
<p>To rebase the last few commits in your current branch, you can enter the following command in your shell:
<br>
<br>
git rebase --interactive HEAD~7
</p>
<br>
<h4>Commands available while rebasing</h4>
<p>There are six commands available while rebasing:
<br>
<br>
<li>
<b>pick</b>
pick simply means that the commit is included. Rearranging the order of the pick commands changes the order of the commits when the rebase is underway. If you choose not to include a commit, you should delete the entire line.
</li>
<br>
<br>
<li>
<b>reword</b>
The reword command is similar to pick, but after you use it, the rebase process will pause and give you a chance to alter the commit message. Any changes made by the commit are not affected.
</li>
<br>
<br>
<li>
<b>edit</b>
If you choose to edit a commit, you'll be given the chance to amend the commit, meaning that you can add or change the commit entirely. You can also make more commits before you continue the rebase. This allows you to split a large commit into smaller ones, or, remove erroneous changes made in a commit.
</li>
<br>
<br>
<li>
<b>squash</b>
This command lets you combine two or more commits into a single commit. A commit is squashed into the commit above it. Git gives you the chance to write a new commit message describing both changes.
</li>
<br>
<br>
<li>
<b>fixup</b>
This is similar to squash, but the commit to be merged has its message discarded. The commit is simply merged into the commit above it, and the earlier commit's message is used to describe both changes.
</li>
<br>
<br>
<li>
<b>exec</b>
This lets you run arbitrary shell commands against a commit.
</li>
</p>


<br>

<h4>Explain in simple terms git cherry-pick and the command for it </h4>
<p>git cherry-pick in git means choosing a commit from one branch and applying it to another branch. This is in contrast with other ways such as merge and rebases which normally apply many commits into another branch.
<br>
<br>
git cherry-pick is just like rebasing, an advanced concept and also a powerful command. It is mainly used if you don’t want to merge the whole branch and you want some of the commits.</p>
<br>
<h4>When to use cherry-pick?</h4>
<p>Suppose a developer fails to recognize which branch he is currently on, and by mistake, he commits to another branch instead of committing to the main branch. Now to fix it, he has to first run git show, then save the commit, check out the main branch, apply a patch there, and commit with the same commit message. But all this can be done automatically by using just one command i.e. cherry-pick.</p>
<br>
<h4>The command for Cherry-pick is as follows:</h4> 
<p>git cherry-pick<commit-hash>
<br>
<br>
<strong>Commit hash:</strong> A commit hash is a unique identifier that is generated by Git. Each commit has its one commit hash.
<br>
<br>

<b>Note:</b> While using this command make sure you are on the branch you want to apply the commit.</p>
<h4>Some important Use Cases of Cherry-pick</h4>
<p>
The following are some common applications of Cherry-Pick:
<br>
<br>
<ol>
<li>
If you by mistake make a commit in an incorrect branch, then using cherry-pick you can apply the required changes.</li>
 <li>
Suppose when the same data structure is to be used by both the frontend and backend of a project. Then a developer can use cherry-pick to pick the commit and use it to his/her part of the project.
 </li>
 <li>
At the point when a bug is found it is critical to convey a fix to end clients as fast as could be expected.</li>
 <li>
Some of the time a component branch might go old and not get converged into the main branch and the request might get closed, but since git never loses those commits, it can be cherry-picked and it would be back.</li>
<ol>
</p>
<br>
<h4>Disadvantages of using Cherry Pick</h4>
<p>Cherry-pick should not be used always as it can cause copy commits and numerous situations where cherry-picking would work, conventional merges are liked all things considered. Also, in the situation where the commits from 2 or more branches update similar lines of code with various substances and git cherry-pick one commit to the other branch, it prompts conflict as well.</p>
<br>
<h4>Conclusion</h4>
<p>Git’s cherry-pick command is a powerful tool for selectively applying specific commits between branches. It’s great for fixing mistakes and sharing code, but overusing it can lead to issues, especially when commits touch the same code lines. So, use it wisely to maintain a clean and efficient code history.</p>