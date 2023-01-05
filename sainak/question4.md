#### Q4. How to delete one commit or multiple commits permanently Write command for it. 


If the commits are in sequence, we can use `git reset` to delete the commits permanently
Else we can use `git rebase -i` to delete the commits permanently

##### Commands:

```sh
git reset --hard <commit-hash>
```
