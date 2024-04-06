# Experiment -3.2 

### 1.	Aim/Overview of the practical: Understanding the various reset modes in GitHub.
### 2.	Task to be done: - Adding two files, commit it then use all the reset command.
### 3.	Steps for experiment/practical: 

1.	Make repository name as my_repository and use cd command to change the directory.
     
 ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/5ef1aab5-1ca7-4988-a2a6-b05979d17923)

2.	Then use git init command to initialize the repository.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/2bdffad5-e8ba-46c2-9ab7-1ea84602fb16)

3.	After initializing it, add two files and add content on these two files using echo command.
   
   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/cbfaec4e-301c-4dcb-b168-b7276bbd46e5)

4.	Then commit these files using commit command.
   
   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/8d20ce81-ebf0-4b2d-8955-1fce0e235621)

5.	After commiting, check the status using git status command and view history using hit log command.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/205c001b-6a75-4092-8e2e-2fc26643160e)

6.	when you run git log -3 --oneline, Git will display the last 3 commits in your repository, each represented by a single line containing the abbreviated commit hash (usually the first 7 characters) and the commit message.
   
In your specific output, it's showing two commits:

•	eb65966: The abbreviated commit hash.

•	(HEAD -> master): Indicates that the HEAD pointer and the master branch are pointing to this commit.

•	added file3.txt: The commit message describing the changes made in that commit.

•	f0c6c7d: The abbreviated commit hash of the second last commit.

•	Added file1.txt and file2.txt: The commit message shows the changes made in that commit.

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/daba773e-82f2-444f-9388-5ce0a4d1c3d4)

7.	Now use git soft command, This option moves HEAD back to the specified commit, undoes all the changes made between where HEAD was pointing and the specified commit, and saves all the changes in the index.

Undo the last commit and move changes to staging area (git reset –soft eb65966)

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/8e630aa7-aaf0-4c07-954e-3c1583da74b2)

8.	Use git mixed command this command Undo the last commit and unstage changes.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/72bebec5-fe2e-44de-9145-5bd0762803db)

9.	Use git reset hard command, this command Undo the last commit and discard changes.

    ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/223cdf43-f395-4aec-b377-d9c32fc7807f)

10.	 Now check the status using git status command.

  ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/57dfc4e6-946e-4e65-a379-2660ea06c66c)



    
### 4. Result/Output/Writing Summary:

In this experiment, we have used all the git reset command to undoing the last commit. This is the most powerful tools Git provides to change to a prior state is the Git reset command.

### 5.Learning outcomes (What I have learnt):

1.Learnt about how to make repository and how to change directory.

2.Learnt how to add files and commit it.

3.Learnt about how to use git reset command.

4.Learnt how to see the history using git log command.

