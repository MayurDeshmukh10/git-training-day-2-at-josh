#### Q2. How to set multiple remote repositories for the same project? Explain the use case. you should have a working demo of it.

Multiple remotes are used to track changes from miltiple remote repo like the upstream or a fork of the upstream
These changes could be then merged or cherry-picked into the origin

##### Commands:

```sh
git remote add <remote-name> <remote-url>
```

![ss](./screenshots/Screenshot%20from%202023-01-05%2016-42-12.png)

here you can see that the remote `upstream` is added to the repo.