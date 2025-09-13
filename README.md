Gittutorial
Hello, This is a complete Git and GitHub Tutorial For Data Engineers Expanded Git & GitHub Notes for Data Engineers Based on: Complete Git and GitHub Tutorial For Data Engineers (2025) by Ansh Lamba

🔹 1. Git Setup & Configuration Commands: git config --global user.name "Your Name" git config --global user.email "your.email@example.com" Explanation: Sets your identity for all Git commits. This info appears in commit history and is essential for collaboration.

🔹 2. Initialize a Git Repository Command: git init Explanation: Creates a .git folder in your project directory, enabling Git tracking. This is the first step in version control.

🔹 3. Check Repository Status Command: git status Explanation: Shows which files are staged, modified, or untracked. Helps you decide what to commit next.

🔹 4. Add Files to Staging Command: git add filename.py Explanation: Moves changes to the staging area. Only staged files are included in the next commit.

🔹 5. Commit Changes Command: git commit -m "Initial commit" Explanation: Saves a snapshot of your staged changes with a descriptive message. Commits are the backbone of Git history.

🔹 6. View Commit History Command: git log Explanation: Displays a list of commits with author, date, and message. Useful for tracking changes and debugging.

🔹 7. Create and Switch Branches Commands: git branch feature-branch git checkout feature-branch Explanation: Creates a new branch and switches to it. Branching allows isolated development without affecting the main codebase.

🔹 8. Merge Branches Commands: git checkout main git merge feature-branch Explanation: Integrates changes from feature-branch into main. Used when a feature is complete and ready for production.

🔹 9. Clone a Remote Repository Command: git clone https://github.com/username/repo-name.git Explanation: Downloads a copy of a GitHub repository to your local machine. Ideal for starting with existing projects.

🔹 10. Connect Local Repo to GitHub Command: git remote add origin https://github.com/username/repo-name.git Explanation: Links your local repo to a remote GitHub repo. Enables pushing and pulling changes.

🔹 11. Push Changes to GitHub Command: git push origin main Explanation: Uploads your local commits to the main branch on GitHub. Keeps your remote repo updated.

🔹 12. Pull Changes from GitHub Command: git pull origin main Explanation: Fetches and merges changes from GitHub into your local repo. Keeps your local copy in sync.

🔹 13. Create .gitignore File Example Content: *.pyc pycache/ .env Explanation: Tells Git to ignore specific files or directories. Prevents sensitive or unnecessary files from being tracked.

🔹 14. View Remote Repositories Command: git remote -v Explanation: Lists the URLs of connected remote repositories. Useful for verifying your GitHub link.

🔹 15. GitHub Pull Requests Steps: • Push your branch to GitHub. • Go to GitHub → Compare & Pull Request → Create PR. • Review and merge after approval. Explanation: Pull requests are how teams review and merge code collaboratively. Essential for clean workflows.

🔹 16. Resolve Merge Conflicts Steps: • Git marks conflicts with <<<<<<<, =======, >>>>>>>. • Manually edit the file to resolve. • Stage and commit the resolved file. Explanation: Conflicts occur when two branches modify the same lines. Manual resolution ensures correctness.

🔹 17. Git Stash Commands: git stash git stash list git stash apply Explanation: Temporarily saves changes so you can switch branches without committing. Useful for quick context switches.

🔹 18. Delete a Branch Command: git branch -d feature-branch Explanation: Deletes a branch after merging. Keeps your repo clean and organized.

🔹 19. Rename a Branch Command: git branch -m old-name new-name Explanation: Renames a branch. Useful for correcting naming conventions or clarifying purpose.

🔹 20. Undo Last Commit (Soft Reset) Command: git reset --soft HEAD~1 Explanation: Removes the last commit but keeps changes staged. Lets you rewrite the commit message or modify files.
