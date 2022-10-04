# How To Use Git and GitHub With Webstorm

---
##   *Important*
    In order to have everything working properly, you will need
    to have downloaded Git (Desktop Version) and Webstorm.
    In addtion, you will need to have a Github account (If not, 
    create one as you will need one to store your code.) In addition, this 
    process was done on a Mac.
---
#### *Overview*
| WebStorm                            | Git                                                         | Github                             |
|-------------------------------------|-------------------------------------------------------------|------------------------------------|
| 1. Have a valid license             | 1. Download **Git** desktop version                             | 1. Create a Github account         |
| 2. Activate key by using NJIT Email | 2. Connect local **repository** to **remote** **repository** on website | 2. Create a **repository** named IS117 |
| 3. Link account with Github account | 3. Sync **remote** **repository** to local **repository**               | 3. Create a Readme file            |

    To begin, you must have created a Webstorm and Github account.
    The links to download the program and to sign up can be found below in the 
    download links section.

---
## *Download Links*
[WebStorm](
https://www.jetbrains.com/community/education/#students)

[Git](https://desktop.github.com)

[GitHub](https://github.com)

---

## *Instructions*

### *Step 1*
After creating an account on **Github**, you must create a **repository**
and give it a name. For this example, we can name as "DEMO". Congratulations! You just created your first **repository**.
### *Step 2*
Open Webstorm, click on **WebStorm** on the top left of the screen. Click on preference. Under version control,
click on GitHub. Click on the + button and connect your **GitHub** account to WebStorm.
### *Step 3*
Under Version Control, click on Git and make sure that WebStorm has automatically found the path
for the Git executable. If not, click on the folder icon and search for the Git.exe . Once done, make sure it works by
pressing on the *test* button. It should output the version of the program.
### *Step 4*
If everything is done correctly, you can now create a new project on Webstorm or get one from VCS. We will be using the 
"Get from VCS" option
### *Step 5*
In this new window, we will be looking for our new **repository** that we created on the **GitHub** website. We will be cloning
this **repository** to our local system.
### *Step 6*
After successfully **cloning** the **repository** to your computer. We will create a new text file and enter "Hello World" in
it. As a result, WebStorm automatically adds these changes to the staging area. All we need to do now is to **commit** the
file by pressing "Command+K". It will prompt you to choose the changes made.
### *Step 7*
After choosing the changes that we made on the txt file, we will add a short meaningful message tha describes the
changes made. Once done, you can click on the "**Commit** and **Push**".
### *Step 8*
As a result, you will see the changes you made to your local **repository** being updated to your 
**remote** **repository** in **GitHub**. Congratulations, you're done!

---
## *Glossary*

| Term           | Defenition                                                                                                                                   |
|----------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Branch         | In Git, the term "branch" refers to splitting out <br/> from the main development directory.                                                 |
| Clone          | Git's clone command copies an existing <br/>  repository into a new directory.                                                               |
| Commit         | The project's staged modifications are <br/> all saved with the git commit command.                                                          |
| Fetch          | The git **fetch** command is used to download commits,<br/>  files, and references into the local<br/>  repository from a remote repository.    |
| Git            | Version Control System                                                                                                                       |
| GitHub         | A remote host to store the repositories you've worked <br/> on on your local machine                                                         |
| Merge          | The various lines of work are combined into a single <br/>  **branch** using the git merge command.                                          |
| Merge Conflict | Git is unable to **merge** the branches  together <br/> as there is a conflict preventing it.                                                   |
| Push           | By using the git push command, you may upload files<br/>  from a local repository to a remote one.                                           |
| Pull           | The git pull command **merge** changes into the local <br/> repository while retrieving and downloading items <br/> from the remote repository. |
| Remote         | It refers as to where your code is being held outside<br/>  of your local machine                                                            |
| Repository     | A folder/directory on Github where all your code is <br/> stored and updated.                                                                |


## *References*

[Slides #1](https://njit.instructure.com/courses/25694/files/3891039?module_item_id=881263)

[Slides #2](https://njit.instructure.com/courses/25694/files/3891026?module_item_id=881262)