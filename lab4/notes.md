Answer 1:--global → configuration is saved at the user level, not inside a specific repo.then Git stores these values in the local repository’s config (.git/config), and they apply only to that specific repo (coding-cafe in this case).
Answer 2: When I ran ls, I saw only the normal files and folders in the repository. When I ran ls -a, an extra entry appeared: .git.

.git is a hidden directory created by git init. It contains all of Git’s internal data for this repository, such as the commit history, branches, configuration, objects (commits, trees, blobs), refs, hooks, and the staging area (index)
Answer 3:3,Yes

