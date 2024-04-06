# Experiment -3.1 

### 1.	Aim/Overview of the practical: Compare the changes in the Git Repository. 
### 2.	Task to be done: - Compare and change. 
### 3.	Steps for experiment/practical: 
 
1.	Create a repository: - Firstly we have to create a new repository using command 
“mkdir”.  
Now we will utilize command “cd” to move to the repository we created.
![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/b99cfb0f-1ae1-4d50-af41-f1a76fad9344)

2. After creating a repository by using the touch command, we will add and modify a test file with name “file.txt”.
![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/fbe56654-7b11-472c-b6e3-0c1429e6fe8d)
 
3.After creating file we need to add content to the “file.txt” file, so we have passed the string “This is exp 3.1”.
![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/2315c7bd-fc59-4594-afb0-1f53068fe846)

 Now by using command “git init” create a blank Git repository – basically a .git  directory. 
 
4.After that use command “git add file.txt” will add file.txt to the staging area. This is the area. Where the files will be added in the next commit. 
 
5.Now we have committed our changes by using “git commit”. When calling git commit, it is required to include a massage. The massage should be a short description of the changes being committed. Though the option -am, you can add and create a massage for the commit in one command. 
![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/4d239b7d-2d92-4fe9-9530-da6441d382c0)

6. Now we will change the contents of file.txt file in our working directory to start experimenting with diff output. After that we check the branch using commands “git branch change and git checkout change”. After that we have to create a file using g” vi file.c command”, and “git add file.c”, After that we have to commit the changes.
  ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/3685aa8b-6869-4151-8a3b-e2606d82ac45)
  ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/a509b3d5-a618-4e7c-92b6-f24e5aad8444)

7. Now we Execute this command, it will change the content of file.txt. Once this file   modified, then we can be able to see the difference and analyse the output.
Now let’s execute “ git diff” command and analyse the results .
![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/71ac8525-9150-4c38-a1ea-0cc3699accd5)

 ### 8. Result/Output/Writing Summary: 
In this experiment, we have merged a file in a branch to the master or main branch on both the local as well as remote repository. 

### 9.Learning outcomes (What I have learnt): 

1	Learnt about cloning of repository, Learnt how to comparing changes in git. 

2	Learnt how to create a pull request and handle their merging. 

3	Learnt about git diff. 

4.Learnt how to resolve merge conflicts. 

