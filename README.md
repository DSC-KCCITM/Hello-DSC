# Hello Developers! <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px">

### Let's help you submit your first Pull Request.
Once your pull request is being merged, your profile will be visible in the Submissions section of this page. For this exercise you'll be adding a ```Hello World``` code in the repository. Excited?  let's begin!

### Step 1:
The first thing we have to do is to configure git with our name and email:  
Open Git Bash and type these commands.
```
git config --global user.name "My Name"
git config --global user.email myemail@gmail.com

```


### Step 2:
Go to the GitHub repository from the link below of this project and fork the project to your account. Click on the fork button on the top right corner of the repository page to do it. Once done, GitHub will take you to the forked copy in your account.
```sh
https://github.com/DSC-KCCITM/Hello-DSC.git
```

### Step 3:
Clone the forked repository to your local machine.  
Click on the big green button saying "Clone or download" and copy the https url of your repository. Fire up the terminal (on linux systems ctrl+alt+t. on Windows open the Git-bash ) navigate to your desired directory and type the following command. Replace the link with the clone URL of your repository and hit Enter.
```sh
git clone https://github.com/YOUR_USERNAME/Hello-DSC.git
```

### Step 4:
Print ```"Hello World, I am YOUR_NAME"``` in any programming language file you prefer and save it.


### Step 5:
Let's start working on the changes required now! First cd into the cloned folder by typing the following command.
```sh
cd Hello-DSC
```
Now, Before jumping in to the code, make sure you're working on a different branch and not in master. To create a new branch, from the terminal inside your current project directory type the following command.
```
git branch hello-YOUR_USERNAME
```
Replace the YOUR_USERNAME with your GitHub username or you can give any name to your branch which describes the purpose of the branch. Since here we're adding a single file, we'll simply give the name of the branch as above. eg: ```git branch hello_haxzie```. Once you have created the new branch we'll change the current brach from master to your newly created branch. Execute the following command on your terminal.
```
git checkout YOUR_BRANCH_NAME
```

### Step 6:
In your  file manager/terminal navigate to the downloaded repo. Open the sub-directory Hello-DSC/contributors/ and create a new .md file with your username as the filename with .md extension.
It should look like YOUR_USER_NAME.md eg: adnankarim.md
Open this file in your favourite editor and fill the details as below in the frontmatter of the markdown file.
YOUR_USER_NAME.md
```
---
username: YOUR_USER_NAME
fullname: YOUR_FULL_NAME
---
```

### Step 7:
Let's commit the changes with a message. First we need to stage all the changes we made. Open the terminal inside the project directory and execute following commands.
```
git add FILE_NAME
```
The above command adds your changes to the staging area, now lets commit it with a suitable and easily understandable message.
```
git commit -m "YOUR_COMMIT_MESSAGE"
```

### Step 8:
Let's push the changes to your repository! execute the following command to push all the changes to the forked copy in your GitHub account.
```
git push -u origin YOUR_BRANCH_NAME
```

### Step 9:
Now, open your web browser and go to the original repository on GitHub. If your changes has been pushed to your forked copy, you'll be able to see an option saying "New Pull Request" in the original repository. Click on the option, on next page choose the master branch of the main repo against your created-branch name ( choose your branch name we created and not master), then click on create pull request. Once you fill in the commit message and comment click on submit pull request, you're all done! Wait for the project maintainer to review your changes and merge it to the master branch. Once its been successfully merged, your changes will be visible in the submissions tab.  


##### Don't forget to ```Star``` the main repository