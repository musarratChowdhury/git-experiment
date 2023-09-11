## Git Reset Command
-- we will see how to revert to either the last commit or any other commit using the commit ID.
-- I have created a file called Readme.md.
-- we add this line for the second commit.

## Git Revert Command

-- Unlike git reset command, git revert command creates a new commit for the reverted changes. The commit where we reverted from will not be deleted.

## Difference between Git Reset and Git Revert : 
-- git reset deletes the reverted commit, but git revert doesnt;
-- git reset does not create a new commit, but git revert does;

## When to use git reset and git revert ; 
    You should use git reset when working on a local repository with changes yet to be pushed remotely. This is because running this command after pulling changes from the remote repo will alter the commit history of the project, leading to merge conflicts for everyone working on the project.

    git reset is a good option when you realize that the changes being made to a particular local branch should be somewhere else. You can reset and move to the desired branch without losing your file changes.

    git revert is a good option for reverting changes pushed to a remote repository. Since this command creates a new commit, you can safely get rid of your mistakes without rearranging the commit history for everyone else.