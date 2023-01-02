# Git Reference

<details>
  <summary><h2> GIT COMMANDS </h2></summary>

### Git Commands


### Git Bash Commands



</details>


<details>
  <summary><h2> CONCEPT NOTES </h2></summary>

### Further Research

</details>

<details>
  <summary><h2> RECIPES </h2></summary>

### Recipe: Make Local Repository
    STEPS TO MAKE A LOCAL REPOSITORY
    - Step 0. Open Git Bash in that particular folder. 
    - Step 1. Type git init (this will make that folder a repository)
    - Step 2. Type git add . (this will add all files to the repository)
    - Step 3. Type git commit -m “Initial commit msg” (all files now in the repository)
    - Step 4. Type git status (you will get a msg, “On branch master nothing to commit, working tree clean” this shows your local repository is finally created)
### Recipe: Push Local Repository to GitHub online
    STEPS TO PUSH A LOCAL REPOSITORY TO A GITHUB REPOSITORY ONLINE
    - Step 0. Open your GitHub profile and create a New Repository. 
    - Step 1. Copy the SSH Key of that created repository.
    - Step 2. Open Git Bash in that particular folder that you want to push. Type git remote add origin PASTE_SSH_KEY_OF_CREATED_REPO. Then type git push origin master –force (type ‘main’ in place of the ‘master’ if your default branch is master)
    - Step 3. Now, refresh your Github page, you will be able to see your committed folders/files there.


### References
- [directory - How to push a new folder (containing other folders and files) to an existing git repo? - Stack Overflow](https://stackoverflow.com/questions/15612003/how-to-push-a-new-folder-containing-other-folders-and-files-to-an-existing-git)
- [How to Push Folders From Local PC to GitHub using Git Commands? - GeeksforGeeks](https://www.geeksforgeeks.org/how-to-push-folders-from-local-pc-to-github-using-git-commands/)

</details>
