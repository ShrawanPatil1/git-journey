# All-in-One Git & GitHub Workflow Cheat Sheet

## Complete Workflow (Start to Remote Sync)

```bash
# 1. NAVIGATION & INITIAL SETUP
cd "folder_name"               # Change directory
cd ..                          # Go back one folder
explorer .                     # Open current folder in File Explorer
git init                       # Turn current folder into a Git repository
git clone <github-repo-url>    # Clone an existing repo from GitHub

# 2. LOCAL CONFIGURATION
git config --local user.email "your_email@example.com"

# 3. STAGING & CHECKING STATUS
git status                     # Check file status and changes
git add .                      # Stage all changes in current directory
git add --all                  # Stage all changes across entire project
git add *                      # Stage all visible changes except deleted files
git restore --staged .         # Unstage all staged files
git restore --staged <file>    # Unstage a specific file

# 4. COMMITTING & UNDOING
git commit -m "Your commit message"  # Save staged changes
git reset HEAD~                # Undo last commit, keep changes in folder
git reset --hard               # Wipe all local changes & reset to last commit

# 5. REMOVING FILES & FOLDERS
git rm -f four.txt             # Force delete file locally and from Git
git rm --cached four.txt       # Remove file from Git tracking ONLY (keep locally)
git rm -r myFolder             # Recursively remove an entire folder

# 6. VIEWING HISTORY
git log                        # Show full commit history
git log --oneline              # Show simplified history on one-line per commit

# 7. BRANCHING & MERGING
git branch                     # List local branches
git branch development         # Create a new branch named 'development'
git checkout development       # Switch to the 'development' branch
git merge main -m "Merging main into development" # Merge 'main' into active branch

# 8. GITHUB REMOTE SYNC (PUSH, FETCH & PULL)
git push origin main           # Push local commits to remote main branch
git fetch                      # Download remote changes WITHOUT merging
git merge                      # Merge downloaded fetch changes into local branch
git pull                       # Fetch + Merge remote changes in one step
