#####Using GitHub Desktop

There are several ways to interact with git and GitHub:
  1. command line git using the Terminal
  1. GitHub Desktop software
  1. the Source Control menu within Xcode
  
These instructions will cover the second option, using the GitHub Desktop software

- let Xcode "create" the git repo for you show here:  https://youtu.be/XvMcmNozy68?t=1m1s
  - this is equivalent to the 'git init' command in command line git
- now open the GitHub Desktop software
- click File > Add Local Repository
- navigate to the new Xcode project you just created
  - here it is important to select the folder that contains the .xcodeproj file, not the folder at the same level as the .xcodeproj file (see attached screenshot)

<img src='http://i.imgur.com/09iofUJ.png' title='Selecting Xcode Project' width='' alt='Selecting Xcode Project' />

- click the Add button
  - at this point, you're just viewing the newly created git repository in GitHub for Desktop.  It is not yet Published (equivalent to "push" in command line git) to your GitHub account.
- now you'll notice without even making any modifications, there are Uncommitted Changes

<img src='http://i.imgur.com/habp6Nu.png' title='Viewing Uncommitted Changes in GitHub Desktop' width='500' alt='Viewing Uncommitted Changes in GitHub Desktop' />

- enter a concise descriptive commit Summary message, add more detail in the Description field if necessary

<img src='http://i.imgur.com/Mrkqp1H.png' title='Commit Message in GitHub Desktop' width='500' alt='Commit Message in GitHub Desktop' />

  - a great 5-min video about the importance of good commit messages: 
    - [Rocky Mountain Ruby 2011 - Lightning Talk: Do Your Commit Messages Suck by: Ryan McGeary](https://www.youtube.com/watch?v=8YjSty6bfog)
- click the Commit to Master button
- now you'll see that there are 'No Uncommitted Changes'
  - now you are ready to 'Publish' (push) the new project to your GitHub account

- click the Publish button

- in the pop up box that appears:
  - give the repo a name, probably best to leave the name that auto-populates as the name of the repo on GitHub (unless you already have a project with this name up in your GitHub account)
    - this name is the name of the git repo on your local machine, and, when auto-created by Xcode, that name is the same as "Product Name" (a.k.a. project name) you chose when you created this new Xcode project
  - you may notice in this screenshot that I have a checkbox to indicate whether to 'Keep this code private' or not
    - this is because have the free Micro account that comes with the [GitHub for Education](https://education.github.com/) pack -- all students should check this out
    
<img src='http://i.imgur.com/Y7DCYa5.png' title='Publish repo details' width='' alt='Publish repo details' />    
    
- click the Publish Repository button
- then you can check out your GitHub account, and you'll see this new repo there
