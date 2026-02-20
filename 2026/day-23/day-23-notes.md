TASK 1:

1. A branch in git is an isolated separate workspace where we can make changes, test any new feature or deployment before actually deploying it to the main branch of any application.

2. Committing everything to main can lead to a lot of conflicts, multiple developers work on a project and each have their definitive assigned role. So, if multiple people make changes in the same part of the file, there can be git conflicts. Secondly, if the team decides to discard anything it is always useful to do that in different branch and then commit the clean working code to main.

3. HEAD in git acts as a pointer to the current branch we are in. It can also indicate if multiple branches have same commit history and whether they are in sync or not. It becomes very important to trace and make sure the history is linear.

4. Files that were committed to the previous branch but do not exist on the new branch are removed from your working directory. Files that exist in both but have different content are updated to match the new branch's version. For uncommitted changes, it tries to carry them to the new branch as a feature, so you can continue working or commit them there. Files that are new and have not been added to Git's tracking (never git added) are generally ignored and remain in your working directory regardless of the branch switch, unless they have the same name and path as a file that is tracked by the destination branch.


TASK 3:

So origin is the remote repository which we clone in our local to add or discard changes and then we push them back to the remote(origin) repo so that the changes reflect in the remotely too. Now for bigger projects/applications first we fork the repo and then clone it. In this case, the forked repo becomes the origin while the the place from where we forked becomes the upstream(the original repo containing source code of the application). In upstream we don't have write and sometimes even execute access, it is read only. If we want our changes to be merged to upstream(main code) then we create a pull request after committing our work to remote(in this case the forked) repo and then after reviewing the request is accepted.


TASK 4:

git fetch downloads changes from the remote repo without altering local files

git pull actually pulls files from remote to local and also merges any changes to current branch, it acts as git fetch + git merge)


TASK 5:

Clone creates a clone of all the files in a remote repo in the local repo. Fork is a github specific feature which creates a copy of a remote repo in your remote account.

Fork is a github specific feature. So you will only fork when you want to make personal changes in that repo directly through your github account. Clone will be used when you want to work in a repo locally.

Use the sync fork option to keep your fork in sync with any changes with the original repo.
