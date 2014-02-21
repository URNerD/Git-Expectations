# The Basics of Git

## Places To Start (And some philosophy)

First the philosophy: commit early, commit often. There is no penalty for making lots of commits – in fact they will make it easier for you and others to understand what has happened to the files in your project. Whenevery you finish a logical group of changes, commit them. Commit before you do something that you think will get messy. Commit when you are done for the day. Commit often.

You won't really understand git (or much of anything) until you are using it. So, get started. The command examples below walk you through a typical change cycle. Try them.

If you'd like to read more about git, here are some sources:

[Git in 5 Minutes](http://classic.scottr.org/presentations/git-in-5-minutes/)

[Git Reference](http://gitref.org/index.html)

## Git Commands To Know

Git is a distributed **Revison Control System**, it lets you manage changes to the files that make up a web site or other project.

These are some of the essential git commands, roughly in the order in which you might use them:

[git clone URL-of-the-repository-you-want-to-clone](http://gitref.org/creating/#clone) - Make a copy of a remote repository. For us this means your repository on GitHub or the class repository on GitHub (https://github.com/URNerD). To make a copy of these notes and the other git materials you could use this command:

git clone https://github.com/URNerD/Git-Expectations.git

[git status](http://gitref.org/basic/#status) - Report on the status of a git repository. This command assumes that your working directory is a git repository – a directory that you created with git clone or git init.

git status

[git add name-of-file-you-want-to-manage-with-git](http://gitref.org/basic/#add) -

[git diff](http://gitref.org/basic/#diff) - 

[git commit [-a] -m "Describe what you did."](http://gitref.org/basic/#commit) -

[git checkout name-of-file](http://gitref.org/branching/#branch) -

[git push](http://gitref.org/remotes/#push) -

[git pull](http://gitref.org/remotes/#push) -