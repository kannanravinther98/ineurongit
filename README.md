## Git commands

### 1.  git --version
This command describes the version installed in the local system.
![image](https://user-images.githubusercontent.com/28582315/196057611-37eb6423-004c-43a8-adc7-6a9c738a171a.png)

### 2.  git init 
This command is used to create a new blank Git repository.
![image](https://user-images.githubusercontent.com/28582315/196057679-0e90b837-ba05-44ca-bf6f-7daa73a7d87a.png)

### 3. git config --global user.name , git config –global user.email <user’s email address>
This commands helps in registering the username and mail id.This will make it easy to know which developer made the changes.
![image](https://user-images.githubusercontent.com/28582315/196057735-014fb407-e460-4a4b-9b45-9fbd2826aade.png)

### 4.git status

![image](https://user-images.githubusercontent.com/28582315/196057825-dbb3a761-06ad-4491-9573-8a8a1c6b0763.png)

### 5.git add .
This command adds all the changes made in the working directory.
![image](https://user-images.githubusercontent.com/28582315/196057895-7637b7d7-e19d-4a9c-9547-81d22b9adeb4.png)

The flow is git add . > git commit -m ''> git push origin main

### 6.git commit -m 'Check in message'
The command for commiting the code in staging environment.
![image](https://user-images.githubusercontent.com/28582315/196057939-91bc58af-427c-494b-8ebe-c374a027ca2b.png)

### 7.git branch
lists all the branches.
![image](https://user-images.githubusercontent.com/28582315/196058035-bb1ba263-780d-42bc-842b-450a81a24656.png)

### 8.git branch -M main
default branch is 'master'. In order to push code, need to change the branch to 'main'.
![image](https://user-images.githubusercontent.com/28582315/196058060-be488182-ff3b-4d6f-b3ef-a8f7ae4f1368.png)

### 9.git remote -v 
gi This command lists the remote connection user has to other repositories.
![image](https://user-images.githubusercontent.com/28582315/196058152-edfdb3c5-85f9-454a-86d2-64382728ddf5.png)

### 10.git pull --rebase origin main
Need to pull before push to avoid merge conflicts later.

![image](https://user-images.githubusercontent.com/28582315/196058329-e0e9e877-25a7-4b32-a9fa-ff2b42e8389b.png)

### 11. git push origin main
This command pushes the changes from stagging to main git repository
![image](https://user-images.githubusercontent.com/28582315/196058412-7edd1ce4-d2da-4daa-95cc-5d78f029b1d3.png)

### 12. git revert
this command is used to revert the changes pushed in the repository.
### 13. git clone
git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location
### 14. git log
This shows the sequence of events performed in the repository
![image](https://user-images.githubusercontent.com/28582315/196058495-dfbbb26c-9294-4cd4-a7f4-5a14ceacfcfb.png)

### 15.This command makes the mentioned branch as the focus branch in which developer can make the changes.
![image](https://user-images.githubusercontent.com/28582315/196058587-76d99aaf-2108-4255-ba1b-71853780f0b0.png)
