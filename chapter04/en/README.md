# Chapter 4: Working with Remote Repositories

## Connecting to a Remote Repository (git remote add)
Connect your local repository to a remote one:
```
git remote add origin <repository-url>
```

**Example:**
You want to back up your project to GitHub. Run `git remote add origin https://github.com/yourname/my-project.git` to connect.

## Pushing Changes (git push)
Send your commits to the remote repository:
```
git push -u origin main
```

**Example:**
After making changes locally, run `git push -u origin main` to upload your work to GitHub.

## Pulling Changes (git pull)
Get the latest commits from the remote:
```
git pull origin main
```

**Example:**
If your teammate made changes, run `git pull origin main` to update your local project.

## Cloning an Existing Project (git clone)
Copy a repository from a remote:
```
git clone <repository-url>
```

**Example:**
To start working on a project from GitHub, run `git clone https://github.com/yourname/my-project.git` to copy it to your computer.
