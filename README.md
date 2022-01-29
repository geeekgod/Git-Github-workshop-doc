# Git & Github

## Topics to be covered:

- What is Git?
  - Setting up Git
  - Basic Git commands
- What is Github?
  - Deep diving into Github
- Creating your first Repository
- Useful features of Github
- Glimpse of Open source

---

## What is Git?

An Open source distributed version control system & lets you manage and keep track of your source code history.

**Version control :** tracks and manages changes to software code.

**Why Git?**

- Easy to maintain code.
- Increases the speed of development.
- Best way possible to work in a team.

### Setting up Git :

1. Download Git Bash for your system:
   - [Download Git Bash](https://git-scm.com/downloads)
2. Install Git Bash
   - Install the Git bash without making any changes in the installation options.
3. Once Installation done you can use Git on your system.

### Git Commands:

1. git
   - To get all the possible git commands with their description.

```
git
```

2. git init
   - To initialize a empty git repository.

```
git init
```

3. git add
   - To add files to the staging area

```
git add <filename>

git add <file1name> <file2name> <file3name>

git add .
```

4. git commit
   - To commit the files which are added to staging area & add a relevant message to your commit.

```
git commit -m "your message"
```

5. git status
   - To get an info about files which are changed & if they are stagged or not.

```
git status
```

6. git log
   - To get the history of commits.

```
git log
```

### Working with branches

7. git branch
   - To get list of branches present in the repo.

```
git branch
```

8. git branch [branch name]
   - To create a new branch.

```
git branch [branch name]
```

9. git branch -d [branch name]
   - To delete a branch

```
git branch -d [branch name]
```

10. git checkout -b [branch name]
    - To create a new branch and switch to that branch

```
git checkout -b [branch name]
```

11. git switch
    - To switch to an existing branch

```
git switch
```

---

## What is Github?

A website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.

**Distributed Version control :** tracks and manages changes to software code which is shared between a team.

**Why Git?**

- One of the biggest community for developers.
- One of the most used software to develop everything.
- Has many outstanding features available which eases the process of software development.

### Outstanding features of Github:

1. Github projects
2. Issues
3. Packages
4. Github pages
5. Github gists

---

## How to add existing local repo to Github

1. Create a Github Repository.

2. Add origin to the remote repo (Github Repo):

```
git remote add origin <url>
```

3. Push to the remote repository:

```
git push -u origin <main-branch-name>
```

### How to work with an existing remote repository

- To clone a remote repo from Github

```
git clone <git-repo-url>
```

- To pull the changes from remote to local repo

```
git pull
```

- To fetch changes from original remote repo but without file transfer

```
git fetch
```

---

## Other useful information:

- Git commands

  - [Read more](https://github.com/joshnh/Git-Commands)

- Git Conventional commits

  - [Read more](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

- Github Student Developer Pack
  - [Read more](https://education.github.com/pack)
