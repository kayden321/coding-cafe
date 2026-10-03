1. `--global` tells Git to save your username and email for your user account on the computer, so they apply to all repositories; without it, the setting applies only to the current repository.

2. `.git` did not appear with `ls` because it is hidden; `ls -a` displays hidden files, so `.git` became visible.

3. Git is offering to track 3 folders/files, and all items listed are files or folders that I created.

4. Nothing disappeared because `.venv/` was already excluded; the only new item shown is `.gitignore`, which was created in Section 3.

5. `.gitignore` should be committed because it stores the rules for files Git should ignore; otherwise, unwanted files could be accidentally shared with others.

6. `README.md` moved from **Untracked files** to **Changes to be committed**, meaning it moved from the working directory to the staging area.

7. The command printed the files added to the main project history with the commit message “lab work so far,” and reported that 5 files changed.

8. It is called the hash.it , a unique short identifier assigned to a commit for future reference.

9. The four steps are: edit existing files, check the status with `git status`, stage the files with `git add`, and commit them with `git commit`.

10. GitHub automatically renders `README.md` from the root directory as the main front page of the repository.

11. It securely saves a local authentication token, so Git no longer repeatedly asks for a GitHub password.

12. GitHub displayed `README.md`, `lab4`, `week02`, and `.gitignore` on the repository’s front page.

13. Pushing does not change local history; it only uploads a copy of the existing local commits to the remote GitHub repository.

14. A private repository is stored on GitHub but visible only to you and authorized collaborators, whereas no repository means the project is not stored on GitHub at all.