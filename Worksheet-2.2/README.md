# Experiment -5

## To Merge Pull Request and Update local repository on GitHub.

1. Aim/Overview of the practical: To Merge Pull Request and Update local repository on GitHub.
2. Task to be done: In this experiment we will merge the pull request and update local repository on git- hub.
   
 ### 3. Steps for experiment/practical:
 
1)	Create the Local Git Repository, then you will need to create a local repository for your file. However, you will need to use equivalent commands for creating folders and navigating the directory structure so that you understand how to merge in Git.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/679dc0c9-d095-452c-8ac5-39b72578f0d0)

 
2) Create the First Git Commit: Once you have created the local Git repository, you need to add some files to the folder.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/9e8212cc-3193-4293-a30b-0573efdc1c36)
   
3) Then add and the commit it.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/1ef41e28-30c4-4991-b0d1-fe25a8f3525f)
   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/47638a40-1842-4892-b2d5-9428cc2d1f7a)
 
4)	Create the GitHub Repository: On your GitHub profile page, select Repositories at the top, then click New.
   
    ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/fc93ec9e-6f7d-46cb-b571-dc5c9b08a4f5)

5)	Push Existing Local Git Repository: Once created, GitHub presents several options for getting started with the new Git repository. You can copy it to your local 
    system, create a new repository on your system and link to it, or import code from another repository.
   
     a) Add remote repository to local and verify the origin’s URL matches the remote repository.
     b) Add git branch and then git push.

     ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/3f7bcada-7079-44d9-af13-61f7e9eaaa1c)

6)	Changes pushes successfully on git-hub through git bash commands.

     ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/6fc443e9-e877-43d5-b069-be951ed4429d)

7)	View Updated GitHub Repository: Back in GitHub, refresh the repository’s page currently display the code examples, and you should see your local files now available in the repository.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/93467df4-ec0e-491a-9a31-caa525ef6a64)

8)	Merge Unrelated Histories: Next, I want to pull down the contents of the GitHub remote repository to my local system, which is just the README.md file. I can 
   accomplish using the git pull command and specifying the origin remote repository and the local main branch.
   
However, this command will result in a fatal error-Fatal: refusing to merge unrelated histories.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/4e28e83e-1f5b-4321-aa9d-80e786d71182)

 
11)	we can force Git to merge the two despite the unrelated histories with the —allow-unrelated-histories parameter, like this:- git pull origin main --allow- 
    unrelated-histories.

    ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/c7e2dee4-a76f-47da-a40b-291a5f3761eb)

12)  Observations/Discussions: we learned how to merge in Git by taking a local code repository and connecting it to a remote GitHub repository. By putting your code 
     in a remote-hosted repository.
    
13) Results: Successfully performed this experiment about merge pull request and update local repositories on git-hub.

