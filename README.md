# Git Commands

Frequently used Git commands

## Clone a git repository
The `url` can be either `https` or `ssh`. 

```git clone `url` ```

Example

```git clone git@github.com:shubhankar1995/gitCommands.git```

<hr />

## Status of repository
Get the difference between the loacl and the version online

```git status```

<hr />

## Add files to commit
Load a file for uploading

```git add filename.txt```

To upload all the files

```git add -A```

<hr />

## Commit
Commit changes

```git commit -m <message>```

Example

```git commit -m "Added a new file"```

<hr />

## Updates from Git
Get the updates from Git

```git pull```

<hr />

## Reset changes
Undo all the changes(Add) made

```git reset```

Undo only a specific file

```git reset filename.txt```

<hr />

## Set the Git profile
Execute the following commands with your details

```git config --global user.name "your_username"```

```git config --global user.email "your_email_address@example.com"```

<hr />

## Rebase branch with master
Execute the following commands with your details

```
git commit -am "CS-XXXX : WIP"
git checkout master
git pull --rebase
git checkout MY_BRANCH
git rebase master
```
