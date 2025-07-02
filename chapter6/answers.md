## Answers

1. Git uses objects to store data: blobs for file contents, trees for directory structures, and commits for snapshots of the project.
2. A Git object is a piece of data stored in the repository, such as a blob, tree, commit, or tag, each identified by a SHA-1 hash.
3. Git’s history is a graph, not strictly linear. Branches and merges create a tree-like structure of commits.
4. References are names that point to commits. HEAD points to the current commit; branches and tags are other types of references.
5. The working directory is the actual files, the staging area holds files to be committed, and the repository stores all commits and objects.
6. `git init` creates a new Git repository by adding a .git folder with all necessary metadata and history tracking files.
7. `git status` shows which files are staged, which are modified, and which are untracked.
8. `git add [file]` moves changes into the staging area so they’ll be included in the next commit.
9. `git commit` saves staged changes, `git commit -a` stages and commits all tracked files.
10. `git log` shows commit history including hashes, authors, and messages.
11. `git diff` shows the differences between files in your working directory, staging area, and last commit.
12. `git checkout [commit ref]` switches your working directory to the state of that specific commit.
13. `git checkout file.txt` restores the file to its state in the currently selected commit.
14. `git branch` lists or creates branches, `git checkout [branch]` switches to one, `git checkout -b [branch]` creates and switches to a new one.
15. `git merge cat` or `git merge dog` combines changes from those branches. If conflicts arise, the user must resolve them manually.
16. `git remote` shows connected remotes; `git remote add origin [url]` adds a remote repository named origin.
17. `git clone [url] [folder]` downloads a complete copy of the repository into the given folder.
18. `git fetch` gets new data from the remote without merging while `git pull` fetches and then merges into your current branch.
19. `git branch --set-upstream-to=origin/master` tells Git which remote branch to track for push and pull operations.
20. `git stash` saves changes temporarily, `git stash pop` restores them, `git blame [file]` shows who last modified each line.
