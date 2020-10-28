# Overview
This repo is to practice and learn to use git effectively. Any code, tips, cheatsheets etc. that I find will be captured here.

## Working locally
I prefer to work on projects on my laptop and have a need to push changes to a github repo. Occasionally I won't be able to work on my laptop and might have to update code on the github repo. I would need to pull any updated/new files from github to my laptop. 

#### Pushing changes to github.com
1. Navigate to the working directory. Run the below if required to initialize git repo.   
```git init```
2. Run below code to create a **remote** git repo:    
```for remote add <name> <url>```
3. Add all files in the directory to be staged.    
```git add .```
4. Commit changes.  
```git commit -m "some comment"```
5. Push committed changes to the repo.  
```git push -u <name> master```

#### Pulling changes from github.com
If changes were pushed to the remote repo using the -u option then a pull request can be made using the below command that lets you do without specifiying the url  
```git pull```  

 If the code was pushed without using -u option then the command would be  
 ```git pull <url>```   
  
   
#### Removing a Remote Reference Locally
If for some reason you need to remove a local remote reference, you can use the following command:  
```git remote rm <name>```  


