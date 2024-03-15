4. The task
You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git. Hint: git switch will make you switch from one branch to another.
![image](https://github.com/Teesha3/MSTGit/assets/157092368/2d5d65c9-d67f-4161-831a-64f1119876a8)
1.	Use git branch to see the two branches that are relevant for this exercise

   ![image](https://github.com/Teesha3/MSTGit/assets/157092368/f1b0b8b2-8669-4f96-906d-6dd5eda1f669)

2.	What branch are you on?
3.	![image](https://github.com/Teesha3/MSTGit/assets/157092368/2e58e2ed-0bbc-4fb2-bc5c-4fa92802d60b)

4.	Use git branch mybranch to create a new branch called mybranch
![image](https://github.com/Teesha3/MSTGit/assets/157092368/61c549e8-b93d-4d96-a527-91678fb96f21)

  
5.	Use git branch again to see the new branch created.
	![image](https://github.com/Teesha3/MSTGit/assets/157092368/23237dc1-a578-4a27-97db-c18fb024200e)

6.	Use git switch mybranch to switch to your new branch.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/902b03e4-a5c5-48c3-a1b7-44c9c0192da0)

7.	How does the output from git status change when you switch between the master and the new branch that you have created?
![image](https://github.com/Teesha3/MSTGit/assets/157092368/25b085b1-26be-45cd-a186-92e16d95aeed)
The branch changes 

    
8.	How does the workspace change when you change between the two branches?

   	![image](https://github.com/Teesha3/MSTGit/assets/157092368/ec6d351e-13b6-4daa-a337-cfee4d8e58fa)
![image](https://github.com/Teesha3/MSTGit/assets/157092368/9d6c4717-e64a-4b5a-a900-8752a8e739ef)

9.	Make sure you are on your mybranch branch before you continue.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/e0524eaf-d5d7-4ba9-a0ef-c88db5d78e0d)

10.	Create a file called file1.txt with your name.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/990b96fe-2a9b-467b-85b4-a0751c2d8485)

11.	Add the file and commit with this change.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/365964c5-d434-4f16-8ae9-deb995d56bfc)
![image](https://github.com/Teesha3/MSTGit/assets/157092368/adf0cb00-0ac0-4ef9-9cdf-c54d3ed1f39e)
![image](https://github.com/Teesha3/MSTGit/assets/157092368/97d6e060-832d-45ae-a75d-d00b21f0869e)

12.	Use git log --oneline --graph to see your branch pointing to the new commit.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/ab8b7ba9-dace-40c1-950b-b3194b1dcc80)
   	

13.	Switch back to the branch called master.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/707b949c-1cca-4e53-bacd-5d87395fcf24)

14.	Use git log --oneline --graph and notice how the commit you made on the mybranch branch is missing on the master branch.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/746d91ee-c048-44b8-9ad5-afc20f567ead)

15.	Make a new file called file2.txt and commit that file.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/a92fc338-dcef-4cfd-9c66-06734e95c8ab)
![image](https://github.com/Teesha3/MSTGit/assets/157092368/bea02116-2bc2-4785-a1d2-fe02a7fa0ee1)

16.	Use git log --oneline --graph --all to see your branch pointing to the new commit, and that the two branches now have different commits on them.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/8be11417-bf00-4b87-a967-6cb699556f73)

17.	Switch to your branch mybranch.

    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/78c875dc-0d25-4745-b59c-a0d12d5c87fa)

18.	What happened to your working directory? Can you see your file2.txt?
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/866b3527-d16c-4802-b51d-39727909fb40)

19.	Use git diff mybranch master to see the difference between the two branches.
    ![image](https://github.com/Teesha3/MSTGit/assets/157092368/ed134e3e-2627-4320-be23-b70327062110)

    
