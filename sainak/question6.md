#### Q5. How to un stage changes from the staged area. write command for it.

To unstage changes from the staged area we can use `git restore --staged <file-name>`
git restore is a new command introduced in git 2.23

Or we can also use `git reset HEAD <file-name>`

##### Commands:

```sh
git restore --staged <file-name>
```

![Alt text](screenshots/Screenshot%20from%202023-01-05%2017-57-07.png)