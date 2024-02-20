# Workshop - The basics of GIT

## Prerequisites
### GIT
#### Install
To start with this workshop, you should install GIT. You can install Git from here: [https://git-scm.com/downloads](https://git-scm.com/downloads).  
Once you have installed GIT, verify your installation by opening your command prompt/powershell/terminal and type:
```bash
git -v
```

#### Configuration
Before you can use git, you need to configure 2 parameters. We shall do this by running these commands:
```bash
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

> Note: replace John Doe and the email with your own name and email (preferably the email that you use for your github account)

### Github
This workshop will use Github, so make you you have a account. If you don't have one, you can create one using the sign up button here: [Github](https://github.com/)

## Creating your first commit
### Step 1 - Fork a repository
If you've created your Github account, and you are logged in, press the fork button in the top right corner of this repository.
![fork repo](./images/fork.png)

Make sure the owner is listed as your own account and leave all options as is. Once you've forked the repository, you should be able to find it under your repositories. Open that repository in Github

### Step 2 - Clone your newly created repository
Now that your repository is open, you should see the same files as there were in the repository that you forked from. Now we will clone this repo to our device.

Start by copying the git url. You can find this if you open the green code button, and under HTTPS there should be a link you can copy.
![clone url](./images/cloneurl.png)

Once you have done that, open your terminal, navigate to whatever folder you'd like the project to be and run the following command:
```bash
git clone https://github.com/<your github name>/git-workshop.git
```

This will clone your repo from github to your local machine in a folder with the same name as the repository.

### Step 3 - Make your first commit
- [x] Clone the repository
- [ ] Change the H1 tag to something of your choosing
- [ ] Stage the change
- [ ] Commit the change
- [ ] Create a file with the name `hobbies.md` and the content of hobbies.txt in the file
- [ ] Stage the change
- [ ] Commit the change
- [ ] Push the changes to Github

> Note: If at any point you are unsure of the files you have staged for a commit, you can use `git status`. This command tells you on which branch you are, as well as which files have been modified/staged, how many commits have been done, etc...

#### Extra challenges
- [ ] Add more sources to the `changePlaceholder` function in `app.js`
- [ ] Add deletion of the placeholder element when the `Delete placeholder` button is clicked

## Branches
### Step 4 - Create and switch to branch
- [ ] Create a branch called `development`
- [ ] Switch to the `development` branch

>  You can verify whether this succeeded when you use `git status` in the terminal.





### Step 6 - Merging branches

#### Updating branches

#### Resolving merge conflicts


### Step 8 - Branch protection



## Resources
[Oh shit, GIT!?!](https://ohshitgit.com/)  
[GIT.WTF!?!](https://git.wtf/)
[Git Book by Scott Chacon](https://git-scm.com/book/en/v2)

https://jonathanmh.com/p/how-to-create-a-git-merge-conflict/