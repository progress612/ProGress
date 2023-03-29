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
commits immutable

what is objects and how they are stored
form of reference in git
what is the "references"
try to write pseudocode for git data model (blob, tree, commit, objects, references)

repositories composition
what git stores and how it works
why staging area

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