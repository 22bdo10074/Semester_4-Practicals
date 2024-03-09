# Experiment -6

## Creation of Forks on GitHub

1. Aim/Overview of the practical: Creation of Forks on GitHub.
2. Task to be done: In this experiment we will create a fork on github.
### 3. Steps for experiment/practical:

  1)	On GitHub.com, navigate to any repository it may be any friend repository or someone else.

 ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/480dcb11-aeff-4798-a757-84e9f2b70c63)

  2)	In the top-right corner of the page, click Fork.

  ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/5d18513d-3a2d-4003-8cd8-b7f5e37f29db)

  3)	Under "Owner," select the dropdown menu and click an owner for the forked repository.

  4)	By default, forks are named the same as their upstream repositories. Optionally, to further distinguish your fork, in the "Repository name" field, type a name.
     
  5)	Optionally, in the "Description" field, type a description of your fork.

  ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/8449d15f-fc09-4e32-a135-ac350ea92ec0)

  6)	Optionally, select Copy the DEFAULT branch only.
     
  7)	For many forking scenarios, such as contributing to open-source projects, you only need to copy the default branch. If you do not select this option, all 
      branches will be copied into the new fork.
  8)	Click Create fork.

  ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/087d2cac-fede-4e67-b48e-cea0f81e8b29)

  9) Cloning your forked repository -Right now, you have a fork the repository, but you do   not have the files in that repository locally on your computer.
       a)	On GitHub.com, navigate to your fork.
       b)	Above the list of files, click Code.
       c)	Copy the URL for the repository.
    o   To clone the repository using HTTPS, under "HTTPS", click .
    o   To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, then click .
    o   To clone a repository using GitHub CLI, click GitHub CLI, then click .

  ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/c7643ae5-93f0-45d1-8ce6-60f068c83ae6)

   d)    Open Git Bash.
   
  10)  Change the current working directory to the location where you want the cloned directory.
  
  11) Type git clone, and then paste the URL you copied earlier. It will look like this, with your GitHub username instead of YOUR-USERNAME:
      
  12) Press Enter. Your local clone will be created.

   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/0f0fd422-622e-451e-ab3d-f9fb824cd8ae)

  13) Configuring Git to sync your fork with the upstream repository-When you fork a project in order to propose changes to the upstream repository, you can configure 
      Git to pull changes from the upstream repository into the local clone of your fork.
      
      a)	On GitHub.com, navigate to the forked repository.
      
      b)	Above the list of files, click Code.
      
      c)	Copy the URL for the repository.
      
      d)	To clone the repository using HTTPS, under "HTTPS", click.
      
      e)	To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, then click.
      
      f)	To clone a repository using GitHub CLI, click GitHub CLI, then click .
      
   14)  Open Git Bash.
       
   15) Change directories to the location of the fork you cloned.
      •	To go to your home directory, type just cd with no other text.
      •	To list the files and folders in your current directory, type ls.
      •	To go into one of your listed directories, type cd project_2.
   16) Type git remote -v and press Enter. You will see the current configured remote repository for your fork.
       
   17) Type git remote add upstream, and then paste the URL you copied in Step 3 and press Enter. It will look like this.
       
   18) To verify the new upstream repository you have specified for your fork, type git remote -v again. You should see the URL for your fork as origin, and the URL 
       for the upstream repository as upstream.
       
        Now, you can keep your fork synced with the upstream repository with a few Git commands.
       
   ![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/5b7ff166-edd5-42fa-ba74-f8227d10d30c)

19) Editing a fork:- You can make any changes to a fork, including:
      •	Creating branches: Branches allow you to build new features or test out ideas without putting your main project at risk.
    
      •	 Opening pull requests: If you want to contribute back to the upstream repository, you can send a request to the original author to pull your fork into their 
         repository by submitting a pull request.
    
20)  Observations/Discussions: we learned how to A GitHub fork is a copy of a repository    (repo) that sits in your account rather than the account from which you forked the data from.  Once you have forked a repo, you own your forked copy. This means that you can edit the contents of your forked repository without impacting the parent repo.
    
21) Results: Successfully performed this experiment about creating a fork on github.

