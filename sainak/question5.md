#### Q5. Difference between --force push and --force-with-lease, You have to show the use of both, also you have to show in what scenario --force-with-lease is used?

`--force` is used to force push the changes to the remote repo. This is used when the remote repo is behind the local repo and the changes are to be pushed forcefully. This is not recommended as it can overwrite the changes in the remote repo.

`--force-with-lease` is safer than `--force` as it checks if the remote repo is behind the local repo before pushing the changes.

from the docs:
This option allows you to say that you expect the history you are updating is what you rebased and want to replace. If the remote ref still points at the commit you specified, you can be sure that no other people did anything to the ref. It is like taking a "lease" on the ref without explicitly locking it, and the remote ref is updated only if the "lease" is still valid.
