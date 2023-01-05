#### Q3. How to combine two commits into one commit? For Example, you have 4 different commits C1, C2, C3, and  C4 and you to combine C2 and C3 into one single commit. 

To combine multiple commits we can squash them in a single commit using git rebase

##### Commands:

```sh
git rebase -i <gitrevisions>
```
![Alt text](screenshots/Screenshot%20from%202023-01-05%2017-30-32.png)
![Alt text](screenshots/Screenshot%20from%202023-01-05%2017-30-02.png)

Here you can see that the commits f194a6e and ebace10 are squashed onto 9cd7fa5 forming a new commit d8553e7
This command overwrites the history of the branch so it should be used with caution.