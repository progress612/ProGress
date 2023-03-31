## [Version Control (Git)](https://missing.csail.mit.edu/2020/version-control/)

what are version control systems
what can it do in solo project
what can it do in team work

Git's data model
what is blob, tree, snapshot and commit
why not linear history (linear history vs DAG snapshot history)
what is this directed acyclic graph of snapshots saying (commit)

```
o <-- o <-- o <-- o <---- o
            ^            /
             \          v
              --- o <-- o
```
commits are immutable

what is objects and how they are stored
form of reference in git
what is the "references"
try to write pseudocode for git data models (blob, tree, commit, objects, references)

repositories composition
what git stores and how it works
why staging area

More

names: blob, tree, commit, check in, check out, stage/index, branch, tag/bookmark, rebase/move, merge, clone and fork, fetch, pull, push 

what is a good commit message
> The seven rules of a great Git commit message
>
> 1. Separate subject from body with a blank line
> 2. Limit the subject line to 50 characters
> 3. Capitalize the subject line
> 4. Do not end the subject line with a period
> 5. Use the imperative mood in the subject line
> 6. Wrap the body at 72 characters
> 7. Use the body to explain what and why vs. how



remote
main: Init -> update
my_feature: Init -> update -> f_change

local
main: Init -> update
my-feature: Init -> update -> f_change

disk
my_feature: Init -> update -> f_change

如何回滚main

- git clone
- git checkout -b my-feature
- git status
- git diff
- git add <file_name> or -a
- git commit
- git push origin my-feature

- git checkout main
- git pull origin main
- git checkout my-feature
## think about why not git merge
- git rebase main
- git push -f origin my-feature

- new pull request
- squash and merge
- delete branch
- git branch -D my-feature
- git pull origin main