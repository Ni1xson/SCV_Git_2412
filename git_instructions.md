![GitHub](GIT.png)
# <span style="color:#177242">__Git User Manual__

## <span style="color:#640CAB"> What is Git?
 #### <span style="color:#640CAB"> -version control

# <span style="color:#ffff00">Manual:

>>## <span style="color:#59afe1">**1.Check your version of Git**

### You can check whether Git is installed and what version you are using by opening up  a command prompt window in Windows, and typing the following command:
```
git --version.
```
 ### If git is installed, a message will appear with information about the version of the program. Or there will be an error message.

>>## <span style="color:#59afe1"> **2.Install Git**

### Download the latest version of git from the official site 
https://git-scm.com/downloads
### Install with default settings.


>>## <span style="color:#59afe1">**3.Git setup**

### The first time you use it, you need to introduce yourself. To do this, you need to enter two commands in the terminal:
```
git config --global user.name "your name"
git config --global user.email your email@example.com
```

>>## <span style="color:#59afe1"> **4.Repository initialization**

### For initialization local repository new folder,enter the command:
```
git init
```


>>## <span style="color:#59afe1"> **5.Append file to next commit**
### Enter your text in ide, and enter the command: 
```
git add<namefile.md>
```
 ### <namefile> is the name of the file, and <.md> file extension.
### After that, your file will be prepared for the next commit.


>>## <span style="color:#59afe1"> **6.Сreating a commit**

### When you have finished writing your text and you want to save
### enter the command: 
```
git commit -m"your message"
```

### Also, if you want to change the last commit, enter the command: 
```
git commit --amend -m "new message"
```

>>## <span style="color:#59afe1"> **7.View actions**

### To view the activity log, enter the command:
```
git log
``` 
### to browse, use the keyboard arrows.
### To view the log in one line, enter the command: 
```
git log --oneline
```

>>## <span style="color:#59afe1"> **8.Сhecking information from git**
### In order to get information about the current status of the git,
 ### enter the command: 
 ```
 git status
```


>>## <span style="color:#59afe1"> **9.Transition between commits**
### Git allows you to move between commits, you can view the status of a file throughout the creation of a file, to do this, enter the command: 
```
git checkout <commit number> 
```
### The commit number is the first four digits of the commit.


>>## <span style="color:#59afe1"> **10.Return to current file**
### In order to return to the current status of the file, enter the command: 
```
git checkout master
```

>>## <span style="color:#59afe1"> **11.View the difference**
### To sight the difference between the current file and the finished one,
### enter the command: 
```
git diff
```


# <span style="color:#00ffff"> result
<span style="color:#00ffff"> * Distributed development

<span style="color:#00ffff">  * Ase of source code management

<span style="color:#00ffff">* Ease and convenience of creating patches

<span style="color:#00ffff">* Fast backporting


>>## <span style="color:#59afe1"> **12.File Ignore**
### In order to exclude qcertain files or folders from tracking in the repository, you need to create a ***.gitignore*** file there and write into it their names or patterns corresponding to such files or folders.

#### <span style="color:red"> create an artificial error))
>>## <span style="color:#59afe1"> **13.Creating branches in Git**

### A branch in git is simply a movable pointer to one of the commits, usually the last one in a chain of commits. The default master branch name in Git is *master*.
### You can create a branch with the command
```
git branch <new branch name>
```
### As a result, a new pointer to the current commit is created.
### The list of branches in a repository can be viewed using the `git branch` command.
### The current branch will be marked with an asterisk: **\*master**
#### <span style="color:red">create an artificial error))

>>## <span style="color:#59afe1"> **14.Merging branches and resolving conflicts**
### To merge the selected branch with the current one, run the following command:
```
git merge <selected branch name>
```
#### <span style="color:red">create an artificial error))
### In case you made a conflict with the master branch (entered the text in the same place but in the master branch), Ide will prompt you to execute one of 4 commands.
### after which you will need to save the commit

>>## <span style="color:#59afe1"> **15.Deleting branches in git**
#### <span style="color:red">create an artificial error))

### In order to delete a branch, you must first transfer all the data using the command:
```
git merge [branch_name]
```
### After you have made sure that everything is done, you can delete the unnecessary branch using the command:
```
git branch -d [branchname]
```
### If you need to delete a branch with unnecessary information, enter the command:
```
git branch -D[name_branch]
```

>>## <span style="color:#59afe1"> **16.Navigate and view branches in Git**
### If you want to see the commit tree, enter the command:
```
git log --graph
```
### Forgot to add that you can use the command:
```
git checkout -b[branchnames]
```
### this command allows you to create a branch immediately with the transition to it)
#### <span style="color:red">create an artificial error))
>>## <span style="color:#59afe1"> **Corollary**
### branches in git are really convenient, they help not to spoil the project and go back if necessary 
:)

#### <span style="color:green">third lesson
>>## <span style="color:#59afe1"> **17.Clone repository**
### lones a repository from github to your local PC command:
```
git clone  [link to repository] 
```
>## <span style="color:#59afe1"> **18.Push to github**
### To send from your local PC to github, use the command:
```
git push 
```

>## <span style="color:#59afe1"> **19.Getting from github**
### to get the current version from github, use the command: 
```
git pull
```