# git-001
Easy way to make own repo  by cloning the repo from other account

step 1 : clone the repo from source account(other account)
```git
git clone https://xxx 
```
step 2: Open VSS directly by following command 
```git
code ....
```
step 3: create the project in any name in your github account  ( don't add any readme.md file at this moment). You can able to see the following code - 
```git
git remote add origin https://xxxxxxxxx
git branch -M main
git push -u origin main
```

step 4: come to your local repo and remove the earlier remote url. Make sure you are in root directory  
```
git remote remove origin
```
step 5: now copy all the above command from step-3 and paste  here - 
```git
git remote add origin https://xxxxxxxxx
git branch -M main
git push -u origin main
```
step 6 : If it ask for any keys/pasword /token, please do that setup 


