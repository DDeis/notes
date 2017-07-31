# Notes

## Git Cheatsheet
### Configuration
- Rebase by default: `git config --global pull.rebase true`
- Set nano as default editor: `git config --global core.editor "nano"`

### Logs
- Viewing Unpushed Git Commits: `git log origin/master..HEAD`

### Commits
- Delete the most recent commit, keeping the work: `git reset --soft HEAD~1`
- Delete the most recent commit, destroying the work: `git reset --hard HEAD~1`
