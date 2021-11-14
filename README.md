# Basic Magit Tutorial for Github


1. Create/Select a repository on Github
2. Clone the Repo to your Local Computer
    `
	 M-x magit-clone
	 `
3. Make your Changes or Add new files in Repo folder
4. In the Repo, press `C-x g` or in minibuffer
   `
    M-x magit-status
   `
5. Check If there are untracked or unstaged files/changes, `press s` to select the particular file
6. Once the status changed to staged, if you want, you can add commit (comments), `press c` (x2)
   6.1. In Commit Section:
	   - press 'C-c C-c' to save and finish, or press 'C-c C-k' to cancel
7. After committing, the `magit-status` will show the commits in the section 'Recent Commits'
8. `Press m` (x2) to merge changes
   - Select the Branch name
9. Message in the minibuffer
   "Git finished"


 _Happy ENDING :)_
