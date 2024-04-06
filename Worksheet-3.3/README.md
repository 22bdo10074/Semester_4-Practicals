# Experiment -3.3

### 1.	Aim/Overview of the practical: Work with your history in Git.
### 2.	Task to be done: - changing the last commit ,changing multiple commit messages, splitting commits and squashing commits.
### 3.	Steps for experiment/practical: 
•	Create a New Git Repository: First, let's create a new directory and initialize it as a Git repository.

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/f81ab339-aa7d-49ee-b891-49623478028d)

•	Make Some Commits: Create some files and make some commits.

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/27bc4e1f-43b1-446d-b6c6-879a6b86efaa)

•	Amend the Last Commit: Let's say we forgot to include something in the last commit. We can amend it. Command (git commit –amend)

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/461eae93-d1ef-463c-bf3e-d957e18fd9f1)

•	Change Commit Message: Now, let's change the message of the last commit.

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/f281c9f6-c1ae-41cd-ba57-72b376510860)

•	Rebase to Squash Commits: Next, let's rebase to squash the last two commits into one.
Command: git rebase -i HEAD~2

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/4b30bdbb-1241-49e2-9b57-61b7e43a4f3c)

•	View History: After rewriting history, it's a good idea to view the commit history to ensure everything looks as expected.
Command: git log –oneline

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/72616f64-f788-4920-9a78-5c7b5f73d0d1)

### 4. Result/Output/Writing Summary: 
In this experiment, we have successfully rewritten history in Git by amending commits, changing commit messages, and squashing commits. Remember to use these commands carefully, especially when rewriting history.

### 5.Learning outcomes (What I have learnt): 

1.Learnt about how to make repository and how to change directory.

2.Learnt how to add files and commit it.

3.Learnt about how to use git amend command.

4.Learnt how to see the history using git log command.
