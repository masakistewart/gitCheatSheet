## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Compares the changes between commits.

#### Repo History
`$ git log` - Shows commit logs.

`$ git log --oneline --decorate --color --graph --all` - (Options) Shows colored changes, draws a graph, pretends as if all the refs in refs/ are listed on the command line as <commit>.

`$ git log -p [filename]` - Shows commit of specific file.

#### Stage files to commit
`$ git add <filename>` - __Fill Me Out__

`$ git add -A` - __Fill Me Out__

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging ####

`$ git merge <branch name>` - __Fill Me Out__