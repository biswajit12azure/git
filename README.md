Git & GITHUB

Authored by:- Biswajit Dash

**Version Control System**

- Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. • It allows you to revert selected files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Like many of the most popular VCS systems available today, Git is free and open source. 

**Types of Version Control System:-**

1. Local Version Control Systems
1. Centralized Version Control Systems
1. Distributed Version Control Systems

![ref3]

**Local Version Control Systems
![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.007.png)**

Local VCSs has a simple database that kept all the changes to files under revision control. One of the most popular VCS tools was a system called RCS, which is still distributed with many computers today. [RCS](https://www.gnu.org/software/rcs/) works by keeping patch sets (that is, the differences between files) in a special format on disk; it can then re-create what any file looked like at any point in time by adding up all the patches.

Local Version Control Systems

**Centralized Version Control Systems
![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.008.png)**
Centralized Version Control Systems (CVCSs) were developed to collaborate with developers on other systems. These systems (such as CVS, Subversion, and Perforce) have a single server that contains all the versioned files, and a number of clients that check out files from that central place. 

This setup offers many advantages, especially over local VCSs. For example, everyone knows to a certain degree what everyone else on the project is doing. Administrators have fine-grained control over who can do what, and it’s far easier to administer a CVCS than it is to deal with local databases on every client.

However, this setup also has some serious downsides. The most obvious is the single point of failure that the centralized server represents. If that server goes down for an hour, then during that hour nobody can collaborate at all or save versioned changes to anything they’re working on. If the hard disk the central database is on 

becomes corrupted, and proper backups haven’t been kept, you lose absolutely everything — the entire history of Centralized Version Control  the project except whatever single snapshots people happen to have on their local machines. Local VCSs suffer 

Systems from this same problem — whenever you have the entire history of the project in a single place, you risk losing ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.009.png)

everything.

**Distributed Version Control Systems**

In Distributed Version Control Systems (DVCSs) (such as Git, Mercurial or Darcs), clients don’t just check out the latest snapshot of the files; rather, they fully mirror the repository, including its full history. Thus, if any server dies, and these systems were collaborating via that server, any of the client repositories can be copied back up to the server to restore it. Every clone is really a full backup of all the data.

Furthermore, many of these systems deal pretty well with having several remote repositories they can work with, 

so you can collaborate with different groups of people in different ways simultaneously within the same project. 

This allows you to set up several types of workflows that aren’t possible in centralized systems, such as Distributed Version Control Systems hierarchical models.![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.010.png)


![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.011.png)   ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.012.png) ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.013.png)![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.014.png)![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.015.png)

![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.016.png) ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.017.png) ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.018.png) ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.019.png) ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.020.png)

Types of Version Control System![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.021.png)![ref1]

10 best version control software

Source code management![ref2]![ref1]

- Source code management (SCM) is used to track modifications to a source code repository. SCM tracks a running history of changes to a code base and helps resolve 

conflicts when merging updates from multiple contributors. SCM is also synonymous with Version control. • As software projects grow in lines of code and contributor head count, the costs of communication overhead and management complexity also grow. SCM is a critical tool 

to alleviate the organizational strain of growing development costs.

Source code management best practices

qCommit often

qEnsure you're working from latest version qMake detailed notes

qReview changes before committing qUse Branches

qAgree on a Workflow

**Git and why is it important?![ref2]![ref1]**

**Git** is a tool used for source code management. It is a free and open-source distributed  ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.022.png)version control system used to handle small to very large projects efficiently. Git is used  to tracking changes in the source code, enabling multiple developers to work together  on non-linear development. 

**It is important** as it track changes effortlessly, and manage code history makes it an  

indispensable tool for developers and projects of all scales &

Git enables users to push (upload) their code changes to GitHub and pull (download) code from **GitHub** repositories, allowing seamless collaboration and version         management among developers.

**Difference between Git and GitHub?![ref2]![ref1]**

![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.023.png)

GIT GITHUB 

- **Git** is a tool used for source code  • **GitHub** is a web-based platform that management. It is a free and open-source  provides hosting for version control using 

  version control system used to handle small  Git. GitHub is a very popular platform for to very large projects efficiently. Git is used  developers to share and collaborate on to tracking changes in the source code . projects, and it is also used for hosting open-source projects.

**Difference Between Main Branch and Master Branch?![ref2]![ref1]**

- By default, GitHub uses the term “*master*” for the primary(older) version of a source code repository. Developers make copies of the “*master*” on their computers into 

  which they add their own code, and then merge the changes back into the “*master*” repo.

- GitHub changed the “master” to be “main” as part of the company’s effort to remove unnecessary references to slavery and replace them with more inclusive terms
- So, bottom line they wanted to get rid of the unpleasant term “master”. Technically its still the same though

**Local Repository![ref2]![ref1]**

- vim test.sh
- git – To see git is installed or not
- git init – To initialize the got repository
- ls –la- To check the files 
- ls .git – contents of git(HEAD, hooks, info, objects, config, description, refs) The *description* file is used only by the Git Web program, 

The *config* file contains your project-specific configuration options, 

The *info* directory keeps a global exclude file for ignored patterns ,that you don’t want to track in a .gitignore file. 

The *hooks* directory contains your client- or server-side hook scripts

The *objects* directory stores all the content for your database, 

the *refs* directory stores pointers into commit objects in that data (branches, tags, remotes and more), the *HEAD* file points to the branch you currently have checked out

**How do you create a new repository on GitHub?![ref2]![ref1]**

1. Go to the GitHub website and log in to your account.
1. Click the “+” icon in the top right corner of the screen and select “New repository”.
1. Enter a name for your repository
1. Add a description of your repository in the “Description” field.
1. Select whether you want your repository to be public or private.
1. Choose a license for your repository(Optional).
1. Click the “Create repository” button.

**Getting Started - First-Time Git Setup![ref2]![ref1]**

- Setting your username and email address in Git is essential for identifying you as the author of commits and contributions in your projects. This information helps Git keep track of who made 

changes to the code. 👤📧 • To set your username and email address, you need to use the following Git commands in the command line or Git client:

- git config --global user.name "Your Name"
- git config --global user.email <your@email.com>
- git config –list

![ref3]

**Local & remote repository? How to connect local to remote?![ref2]![ref1]**

- **The local repository** is a Git repository that is stored **on your computer.**
- **The remote repository** is a Git repository that is stored on **some remote computer.**
- The remote repository is usually used by teams as **a central repository** into which everyone pushes the changes from his local repositor

**To connect local to remote repository**

- Initialize git repository using #***git init*** in local repository
- Create repository on github account

Cloning an Existing Repository

- Git clone <url>
- In your local repository, run the following command to add the remote repository
- ***git remote add origin <remote repository URL>***

remote repository URL → Copied URL of the remote repository.

Using command, we can check that local repository is connected to remote repository or not

- ***git remote –v***
- ***git branch*** 
- ***git branch –M main***
- ***git push origin main or git push –u origin main![ref3]***


Git Branch![ref2]![ref1]

- **git branch** –To check the branch ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.024.png)
- **git branch –M main** – to rename 
- **git checkout <branch name>  -** to navigate 
- **git checkout –b <branch name>** - create branch 
- **git checkout –d <branch name>** - delete branch 
- **git merge <branch name>** - merge branch 

Merge code![ref2]![ref1]

- git diff main –To check difference between branches
- git merge <branch name>
- pull request- It lets you tell others about the changes you have pushed to branches of the repository.
- git pull - Pull remote changes to local repository
- Merge conflicts- If merge conflict occurs then do the changes

**Other git commands![ref2]![ref1]**

- git status –To track the files in git for versioning
- git diff – to check the exact changes of files in git
- git add – to add the untracked files or modified files to git
- git commit –m “message” – after adding to commit the changes
- git log –To check the number of commits happened and track the versioning
- git reset --hard  <commit id>/ git reset HEAD~1/ git reset <filename>  -To switch version in git
- git rm –To remove file
- git mv – to move or rename files

Fork![ref2]![ref1]

- A Fork is new repository that shares code and visibility settings with original upstream repository. It is a rough copy.

![ref3]

**Git Revert and Reset![ref2]![ref1]**

Git revert and reset are two commands that can be used to undo changes in a Git repository. However, they work in different ways. ![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.025.png)

**git revert** 

- The git revert command creates a new commit that undoes the changes made by the specified commit. This means that the commit history is preserved, and other developers can still see the changes that were made, even 

  though they have been undone.

- To use the git revert command, simply specify the commit that you want to undo: git revert <commit-hash>
- This will create a new commit with the message "This reverts commit <commit-hash>".

**git reset**

- The git reset command moves the HEAD pointer back to the specified commit. This means that the commit history is rewritten, and any commits that were made after the specified commit are discarded.
- To use the git reset command, simply specify the commit that you want to move the HEAD pointer back to: git reset <commit-hash>
- This will reset the HEAD pointer to the specified commit, and any commits that were made after the specified commit will be discarded.![ref3]


**Git Rebase and Merge![ref2]![ref1]**

In general, you should use git rebase to combine changes from one branch into another when you are      working on your branch and you want to keep the commit history linear. You should use git merge when you are working on a shared branch and you want to preserve the commit history.

**git rebase git merge![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.026.png)**

- The git rebase command moves the commits  • The git merge command combines the changes from one branch onto the tip of another branch.  from two branches into a single branch. This is 

  This means that the commit history is rewritten,  done by creating a new commit that contains the and the two branches will have a linear history. changes from both branches.

- To use the git rebase command, simply specify  • To use the git merge command, simply specify the branch that you want to rebase onto: git  the branch that you want to merge into the 

rebase <branch-name> current branch: git merge <branch-name> • This will move the commits from the current  • This will create a new commit that contains the branch onto the tip of the specified branch. changes from both branches.

git fetch and git pull![ref2]![ref1]

Git Fetch Git Pull

- The Git fetch command only downloads new data  • Git pull updates the current HEAD branch with from a remote reposit the latest changes from the remote server.
- It does not integrate any of these new data into  • Downloads new data and integrate it with the your working files. current working files.
- Command - git fetch origin • Tries to merge remote changes with your local git fetch --all • onGiteps.ull = git fetch + git merge

Command - git pull origin master

![ref3]

Q & A![ref2]![ref1]

What is the functionality of git ls-tree?

The git ls-tree command is used to list the contents of a tree object.

What is Git stash?

- Let’s say you're a developer and you want to switch branches to work on something else. The issue is you don’t want to make commits in uncompleted work, so you just want to get back to this point later. The solution here is the Git stash.
- Git stash takes your modified tracked files and saves it on a stack of unfinished changes that you can reapply at any time. To go back to the work you can use the stash pop.

What is Git stash vs Git stash pop?

Git stash pop removes the (topmost, by default) stash when applied, whereas git stash apply keeps it in the stash list for future use.

What does the git reset --mixed and git merge --abort commands do?

- git reset --mixed is used to undo changes made in the working directory and staging area.
- git merge --abort helps stop the merge process and return back to the state before the merging began.

What exactly is git cherry-pick?

A command typically used to move specific commits from one branch of a repository to another.

State the difference between “git remote” and “got clone”?

- “Git remote” allows you to create an entry in the git configuration which specify a URL.
- “Git clone” lets you create a new git repository by letting you copy it from the current URL.

What is Git Bisect and how do you use it?

- The Git Bisect command performs a binary search to detect the commit which introduced a bug or regression in the project’s history.
- Syntax: git bisect <subcommand> <options>

What is the functionality of git clean command?

The git clean command removes the untracked files from the working directory.

How to change any older commit messages?

You can change the most recent commit message with the git commit —amend command.

Explain git reflog

This command is used by Git to record changes made to the branches' tips. ![ref3]Role of the git annotate command. 

In git, it is used to track each line of the file based on the commit information. 

THANK YOU ![ref1]![](Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.027.png)

BISWAJIT DASH  ||   ISHA DEVOPS

**Subscribe YouTube Channel for more Contents :   ![ref3]https://www.youtube.com/@IshaDevops** 

[ref1]: Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.002.jpeg
[ref2]: Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.005.png
[ref3]: Aspose.Words.ad62aed8-3fb5-45c0-8b30-cdcddcdbb489.006.png
