# My Github Guide
## My steps on how to upload something on github

### Before you can you can do all this you first of all create a new repository on GitHub
#### Step 1. First of all using cd you enter the directory you want to push to github.
#### Step 2. Type git init to initialize all your files (be careful not to type this twice for no reason, it will land you in a big error).
#### Step 3. Type git status all your files should be a color of red.
#### Step 4. Then type git add . (including that space and the dot don't ignore it because it is small but mighty)
#### Step 5. Now type git status again and your files should be a color of green.
#### Step 6. Type git config --global user.name to be sure it's your github account.
#### Step 7. Type git config --global user.email to be also sure it's the corresponding email address.
#### Step 8. If its not your git account name and or your github's account's corresponding email address then after typing the two commands above, give a space and then type your github account name or your corresponding email address.
#### Step 9. Type git push, it should say no configured push destination.
#### Step 10. Copy the link of your new github repository and then type git remote add origin (the copied link of your new github repository)
#### Step 11. Now type git remote -v to check if the link corresponds with what you have on your browser.
#### Step 12. Type git commit -m "Whatever name you want", it should show some things like "create mode 100644" for all your files
#### Step 13. And finally type git push -u origin master 
### NOTE: This might take a while depending on your internet speed, size of your files and number of files you want to upload to your github repository.
