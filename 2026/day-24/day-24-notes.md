TASK 1:

A fast-forward merge is a type of merge which takes place when you want to merge a branch with some new commit(s) to the target branch which has no new commit.

Git creates a merge commit when new commits are made both in the branch and the target branch.

Merge conflict occurs when some changes are made in same part of a file in two different branches and you want to merge those two branches.


TASK 2:

Rebase creates a single timeline of commits made in two different branches and shows it as linear based on the timing of commit.

The history will show branch earlier but after rebase it will be linear from the branching point

In a team work rebasing is a very bad idea because it breaks the record of history. Rebasing recreates new commits and hash. This will lead to different histories and someone other might face problems while pulling or commiting.

Merge is a good option when a branch is shared with manhy people and we want to keep a trail of the commits. The history is maintained and commit hashes are not changed with merge. Rebase on the other hand is recommended only when you are working alone. It makes the history linear and clean. It also removes merge commits. 


TASK 3:

Squash merge clubs a number of commits and creates a single commit

If you want to maintain a clean branch for main, use squash merge. While normal merge is good for a detailed history when multiple people are committing

Detailed commit history is lost in squash merge, that is the trade-off


TASK 4:

git stash pop deletes the stash after change but git stash apply keep the stash record

git stash should be used when you want to pause your progress of an uncommitted file in a branch and do some other changes to the same file but in different branch. You don't want the changes from previous branch containing that uncommitted file to reflect.


TASK 5:

cherry-pick helps to select one specific commit from number of commits and applies only that to the branch

When only one committed feature out of many others will be required to be added, we will use cherry-pick







