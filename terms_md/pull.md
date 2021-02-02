# Pull 

## Definition
* Used to fetch and download content from a remote repository and thus updates the local repository to match that content [1]
## Examples

Grabs the specified remote repository copy of the current branch and then merges it into the local copy.
```
git pull <remote>
```

Syncs up your local repository with the central repository. This simply moves the work of the local copy on top of what has been contributed
on the central repository.
```
git pull --rebase <remote>
```

Displays what content has been downloaded and the merge details.
```
git pull --verbose
```

Sources:
* [Git Pull](https://www.atlassian.com/git/tutorials/syncing/git-pull)

[Link to Previous Page](/terms.md)