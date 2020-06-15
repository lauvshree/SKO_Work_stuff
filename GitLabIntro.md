## Objective of the document
At the end of this reading, you will be able know
1. How to get access to a project
2. Which branch should we use
3. What does a project folder structure look like
4. When to issue merge/push/pull requests
5. Who is responsible for review
6. And how to publish in Coursera and edX

### Getting started with GitLab

1. Create a GitLab account with your SkillUp email.

2. Request to be added as a SN Author by going to https://skills.network/authoring/  and clicking on the big red button “Become a Skills Network Author”
![image005](https://user-images.githubusercontent.com/43871747/84617036-65ff5000-aeeb-11ea-9d10-199719635f50.jpg)

3. This takes you to a page where you can fill out a form giving all the details requested.
![image006](https://user-images.githubusercontent.com/43871747/84617033-626bc900-aeeb-11ea-91fc-08478849be40.jpg)


4. Once this process goes through you should be added to be added to the DB0201EN (SQL for Data Science) course project on the IBMSkillsNetwork.

5. Verify the same by going to this [link](https://gitlab.com/ibm/skills-network/courses) and under the listed `Subgroups and Projects` choose `DB0201EN - SQL for Data Science`

6. If you don't see any `Subgroups and Projects`, you are in all probabilities not added as an author in the skills network. Please repeat step 2 and/or follow-up with IBM.

7. Once you can see the contents of the project `DB0201EN - SQL for Data Science`, you can now work on it. 

8. Every project you work on has a main copy which is called the `master`. You always take care that the master is always in working order. You never make changes to the master without making it doubly sure that it will all work. 

9. Given below are two ways to work on the project. 

### Forking
    a. You can choose to fork the repository, by clicking `Fork` on the top right corner of the page here under. This will create your own mirror image of the repository in your namespace (under you login). The mirror image comes with the original repository and its branches. 
    
    ![image](https://user-images.githubusercontent.com/43871747/84616919-fd17d800-aeea-11ea-97b2-bc49b3d3b8f2.png)
    
    b. This approach is often useful if you want to make changes on top of what exists but have less or no need to push the changes you have done back to the source you copied from. 
    
### Branching
   a. This is recommended when you are working on small fixes. While you are in the process of making the fixes, you don't want to disturb the `master`
   b. To create a branch, click on the `+` drop down and choose `New Branch` and then give a name to your branch that is appropriate and easy to identify. 
   <img width="1032" alt="Screen Shot 2020-06-15 at 2 52 17 pm" src="https://user-images.githubusercontent.com/43871747/84655083-f3639400-af2d-11ea-92b3-07e74fe29b5d.png">
   c. Once you create a branch, any changes that you make and commit in the branch, stays with the branch unless you decide to merge the branch to the master. 
   d. If you want the changes in the branch to reflect in the master we merge the **branch** to the **master**
    
   e. On the other hand, if you want to keep the branch aloof but make sure any changes to the master reflects on your branch, you do a merge from **master** to **branch**. This is often referred to as `pull`.
   
<img width="1440" alt="Screen Shot 2020-06-15 at 5 36 20 pm" src="https://user-images.githubusercontent.com/43871747/84655770-2ce8cf00-af2f-11ea-859b-daed568e484e.png">

   f. The owner of the repository may or may not enable conditional commit which will require any code that is pushed to the master to be reviewed before approving. When such permissions are set and you raise a merge request, it goes to the master as an open request which can be reviewed and approved. 

The structure of a project in GitLab is identical to a directory or folder structure on the desktop. This makes it easy to seamlessly navigate.


### Cloning you repository on your computer
##### HTTPS Clone - 
To create a clone of the master, you can use `git clone <httpslinkToRepository>`. In the following example https://gitlab.com/lavanyats/demoproject.git is the repository link. 

git clone https://gitlab.com/lavanyats/demoproject.git

To create a clone of a particular branch, you can use `git clone --branch <branchname> <httpslinkToRepository>`. In the following example https://gitlab.com/lavanyats/demoproject.git is the repository link and branch1 is the name of the branch. 

git clone --branch branch1 https://gitlab.com/lavanyats/demoproject.git





