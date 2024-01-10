# Git Workflow Practice Exercises:

## Initialization and Status:

1. Clone Git repository for a project.
2. Check the status of the repository using `git status`.

## Staging and Committing:

3. Create a new file named "example.txt" and add some content to it.
4. Add the "example.txt" file to the staging area using `git add .`.
5. Commit the staged changes with a meaningful commit message using `git commit -m '<commit message>'`.
6. Create another file named "notes.txt" and add it to the staging area.
7. Commit the "notes.txt" changes with an appropriate commit message.
8. Modify the "example.txt" file and check the diff using `git diff`.
9. Stage and commit the changes made to "example.txt".

## Working with Commits and Logs:

10. Use `git log` to view the commit history.
11. Filter the log using the `--author`, `--since`, and `--grep` options.
12. Check the changes introduced in a specific commit using `git show`.

## Undoing Changes:

13. Undo the last two commit by using `git reset --soft HEAD~2`
14. Remove "notes.txt" from the staging area using `git restore --staged`.
15. Undo the changes made to "example.txt" in the working directory using `git reset` and `git restore`.
16. Add more contents at least 3 additional lines in "example.txt" file, then stage/commit the changes made.
17. Amend the last commit's message using `git commit --amend -m '<amended commit message>'`.
18. Recover the content of "example.txt" from a previous commit using `git checkout <SHA> <file name>`.
19. Undo the changes made to "example.txt" using `git reset` and `git restore`. 

## Ignoring and Removing Files:

20. Create a `.gitignore` file and add patterns to ignore certain files.
21. Add and commit the `.gitignore` file.
22. Create "node_modules" folder
23. Add "node_modules" and "notes.txt" to ".gitignore"
24. Remove "notes.txt" from both the working directory and the repository using `git rm`.
25. Stage/commit the changes made.
26. Create "notes.txt" file and check if "notes.txt" file is ignored.
27. Create "untracked.txt" file, and check if the file is untracked with `git status`
28. Clean untracked files from the working directory using `git clean`, dry run first and clean with interactive mode.

## Resetting Commits:

29. Reset the last commit using `git reset HEAD^`.
30. Stage/commit again
31. Reset the last two commits using `git reset HEAD~2`
32. Stage/commit again
33. Revert the changes made in ".gitignore" file using `git show <SHA>` and `git revert <SHA>`.

## File Operations and Renaming:

34. Use the `mv` command to rename "example.txt" to "new-example.txt".
35. Stage and commit the renaming of the file.
