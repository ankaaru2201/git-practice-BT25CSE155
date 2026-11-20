# Git Commands Record

| Command | Purpose |
|---|---|
| git --version | Check Git version |
| git clone URL | Clone a repository |
| git init | Initialize a repository |
| git status | Check repository status |
| git add . | Stage all changes |
| git commit -m "message" | Save changes |
| git push origin main | Upload changes |
| git pull origin main | Download latest changes |
| git branch | List branches |
| git branch branch-name | Create a branch |
| git switch branch-name | Switch branches |
| git switch -c branch-name | Create and switch branch |
| git merge branch-name | Merge another branch |
| git log --oneline | View commit history |
| git diff | Compare changes |
| git rm -r folder-name | Remove a folder |
| git remote -v | View remote repositories |

## Merge Conflict Experience

Created two branches:
- feature/conflict-a
- feature/conflict-b

Modified conflict-demo.txt differently in both branches.

Git reported a merge conflict when the branches were merged.

Resolved the conflict manually by editing the file, removing conflict markers, staging the resolved file and committing the changes.

## Conclusion

Practised essential Git commands and successfully resolved a merge conflict.
