# Understanding Differences

## Git Vs Github

| Aspect              | Git                                        | Github                                                    |
|---------------------|--------------------------------------------|-----------------------------------------------------------|
| Definition          | Distributed version control system.        | Web-based hosting service for Git repositories.           |
| Functionality      | Tracks changes in files locally.           | Hosts repositories in the cloud, facilitating collaboration, issue tracking, and more.|
| Usage               | Installed on local machines for version control. | Provides a platform for sharing and collaborating on Git repositories. |
| Examples            | Git commands like `git add`, `git commit`, `git push`. | Github features pull requests, issue tracking, and repository management. |


## Git merge Vs Git rebase

| Aspect                  | Git Merge                                               | Git Rebase                                             |
|-------------------------|----------------------------------------------------------|--------------------------------------------------------|
| Operation               | Integrates changes from one branch into another.         | Integrates changes by moving the branch to a new base. |
| Resulting History       | Maintains the original branch history.                  | Creates a linear history by incorporating changes on top of another branch.|
| Merge Conflicts         | May result in merge conflicts, which need resolution.   | Conflicts are encountered during rebase and need resolution at each commit. |
| Workflow                | Suitable for preserving context and collaboration.      | Preferred for maintaining a cleaner, linear project history.|


## Git pull Vs Git fetch

| Aspect                  | Git Pull                                                  | Git Fetch                                                 |
|-------------------------|-----------------------------------------------------------|-----------------------------------------------------------|
| Operation               | Fetches changes and merges them into the current branch. | Retrieves changes from a remote repository without merging.|
| Automatic merging       | Automatically merges fetched changes into the current branch. | Requires manual merging after fetching changes.          |
| Use Cases               | Quick way to update local branch with remote changes.    | Useful for reviewing changes before integrating them.     |
| Impact on History       | Creates a merge commit, affecting the commit history.    | Does not alter commit history until merged explicitly.    |


## Git revert Vs Git reset

| Aspect                  | Git Revert                                               | Git Reset                                               |
|-------------------------|----------------------------------------------------------|---------------------------------------------------------|
| Action                  | Creates a new commit to undo specified changes.          | Moves the HEAD and possibly modifies index and working directory.|
| Effect on History       | Maintains the existing commit history.                   | Rewrites commit history, potentially discarding changes. |
| Safety                  | Safer, as it doesn't alter existing commits.             | Riskier, as it can discard commits and their changes.   |
| Use Cases               | Preferred for reverting changes on shared branches.      | Useful for undoing local changes or resetting the repo to a certain state. |

## Stashing and Checkouts

| Aspect                  | Stashing                                                  | Checkouts                                                |
|-------------------------|-----------------------------------------------------------|-----------------------------------------------------------|
| Functionality           | Temporarily shelves changes to work on something else.    | Switches between different branches or commits.          |
| Use Cases               | Useful for saving work in progress without committing.    | Facilitates working on different features or branches.   |
| Command                 | `git stash`                                              | `git checkout <branch/commit>`                           |
| Workflow                | Provides a way to store changes without committing them. | Essential for navigating through project history.        |

## Submodules and Subtrees

| Aspect                  | Submodules                                                | Subtrees                                                 |
|-------------------------|-----------------------------------------------------------|-----------------------------------------------------------|
| Inclusion               | Includes separate Git repositories within a parent repository. | Incorporates contents of one repository into another.    |
| Version Control         | Maintains separate version histories for each submodule.  | Merges entire repository history into the parent.        |
| Updates                 | Submodules need to be updated manually after changes.     | Updates are managed directly within the parent repository.|
| Management              | Requires additional commands for submodule management.    | Offers a simpler workflow for managing dependencies.     |
