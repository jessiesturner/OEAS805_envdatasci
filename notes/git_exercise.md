## Git setup and workflow

# Configure git

First check that you have git properly installed on your machine and get it configured. Check the version of git you are running.

```
git --version
```

Now configure git with some global variables, your `user.name` and 'user.email' which should be the same as those used to set up your GitHub account.

```
git config --global user.name "<USER_NAME>"

git config --global user.email "<USER_EMAIL>"
```

Now check that your configuration is what you expect:
```
git config --list
```

# Create your project repository

Now we're going to create a new folder for your project. It's a good idea to keep your file system well organised and so I suggest that you make a separate folder specifically for this class, call it whatever you would like, but avoid using an spaces in your folder or file names. Once you have a folder set up for the class, make a folder in it for this exercise. 

```
mkdir OEAS805

cd OEAS805

mkdir git_exercise

cd git_exercise
```

Now that we have created a directory for this exercise, we can **initiate** it as a git repository.
```
git init
```
You can check whether or not a folder is a git repository by running an 'ls -a' command to list the files in the folder. If your folder contains a '.git' subdirectory, then it is a git repository and changes can be tracked.

For a full list of git commands, use the 'git --help' command to list them in the shell, or use the 'git help everyday' command to get a handy list and explanation of the commands you are most likely to use depending on what your role is in a project.

# Git workflow

Git does not track changes you make to your project automatically. You need to **add** and then **commit** changes to your project as you make them. After your run the 'git add' command on a file that you have changed, you don't have to repeat the filename in the 'git commit' command, it will commit any files that you have added in the 'git add' step. When you commit changes, you will also add a short text string to explain the changes you have made. Here's an example:
```
git add hello.txt

git commit -m 'wrote hello world text file'
```
You can use 'git log' to print information about your commits to the terminal. If you want to see line by line differences in a 

I will not cover the branch feature of git and GitHub in this class, but you may find it useful in future work if you are working on a project with multiple people coding at the same time. In that case, you would want to create a parallel branch in your repository, then you will use the 'git branch' and 'git checkout' commands. Once you have made changes in the new branch, tested them and decided that you want to incorporate them into the main branch of the project, you'll run a 'git merge' command.

# Git workflow - the first time for a directory

Starting a Brand New Project (First Time Only)
Run these commands in your project folder to set up Git and connect it to a newly created GitHub repository.

1.Initialize Git locally:
Turn your local folder into a Git repository. Make sure there are files in the folder.
```
git init
```

2.Stage your files:
Add all files in your current directory to the staging area.
```
git add .
```

3.Commit your changes:
Save a snapshot of your staged files locally with a descriptive message.
```
git commit -m "Initial commit"
```

4.Rename the branch to main:
Ensure your default branch matches GitHub's standard naming (main).
```
git branch -M main
```

5.Link to your online (remote) GitHub repository:
Connect your local repository to the empty repo you created on GitHub (replace the URL with your actual repo link). This may be different for different computers and you may need to create an SSH key. If you created an SSH key write it down somewhere.
```
git remote set-url origin git@github.com:your-username/your-repo.git
```

6.Push your code to GitHub:
Upload your local commits to the remote GitHub repository.
```
git push -u origin main
```

# Git workflow - after already linked to online repository
Updating an Existing Project (Everyday Workflow)
Once your project is linked to GitHub, sending new changes takes just three commands:

1.Stage modified files:
```
git add .
```

2.Save changes locally:
```
git commit -m "Describe the changes you made"
```

3.Push to GitHub:
```
git push
```


  
