# Git Reference


<details>
  <summary><h2> COURSES </h2></summary>

_This is a collection of some nice courses, youtube lectures and weblinks which i found useful to understand the concept and workings of Git._
  
  (0). Two courses online
  - [Version Control of a Python Project using Git (Coursera)](https://www.coursera.org/projects/version-control-of-a-python-project-using-git)
  - [Git from Scratch (Linkedin Learning)](https://www.linkedin.com/learning/git-from-scratch/git-from-scratch?autoplay=true)

  (1). This is by far the best intro ever. Period. A really nice introduction for the uninitiated!
  - [Git Tutorial For Dummies by Nick White - YouTube](https://www.youtube.com/watch?v=mJ-qvsxPHpY)
  
  (2). A good short intro   
  - [Python Version Control With Git and Github - #7 - YouTube](https://www.youtube.com/watch?v=yYknmU_gBgs&t=20s)
  
  (3). This is a video on the creator of Git and Linux   
  - [The mind behind Linux | Linus Torvalds - YouTube](https://www.youtube.com/watch?v=o8NPllzkFhE&t=9s)
  
  (4). This is a good series!   
  - [Git and GitHub for Poets by Daniel Schiffman - YouTube](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)

  (5). This is way more advanced.
  - [Git Crash Course - A Simple Workflow for Small Teams and Startups](https://www.zachgollwitzer.com/posts/git-course)
  - [Git Crash Course for Beginners (part 1/3) - YouTube](https://www.youtube.com/watch?v=kmGsHjQ2wsY&t=176s) 
 
</details>


<details>
  <summary><h2> GIT COMMANDS </h2></summary>

### Git Commands


### Git Bash Commands



</details>


<details>
  <summary><h2> CONCEPT NOTES </h2></summary>

I dreamt about this just before sleeping: Git it like a Cactus which grows. I googled it and there came some astonishing and interesting findings.
  

### Further Research
  
[git is like a cactus - Google Search](https://www.google.com/search?q=git+is+like+a+cactus&oq=git+is+like+a+cactus&aqs=chrome..69i57.939j0j7&client=ms-android-huawei-rev1&sourceid=chrome-mobile&ie=UTF-8)
#### STREAM  1
  - [ ] [Cactus Model | The Git Workflows Warehouse](https://gitworkflows.cs.manchester.ac.uk/workflow-catalogue/cactus-flow/)
  - [ ] [Hustle/git-cactus: 🌵 Git tool for Cactus Branching Model 🌵](https://github.com/Hustle/git-cactus)
#### STREAM 2
  - [ ] [Git Flow vs. Trunk Based Development | Toptal](https://www.toptal.com/software/trunk-based-development-git-flow)
  - [ ] [Git Crash Course: A Simple Workflow for Small Teams and Startups | by Zach Gollwitzer | Medium](https://zach-gollwitzer.medium.com/git-crash-course-a-simple-workflow-for-small-teams-and-startups-c491919c9f77)
  - [ ] [Git Crash Course for Beginners (part 1/3) - YouTube](https://www.youtube.com/watch?app=desktop&v=kmGsHjQ2wsY&feature=youtu.be)
  - [ ] [Open Educational Resources on GitLab](https://oer.gitlab.io/) _
  - [ ] [Git Tutorial - javatpoint](https://www.javatpoint.com/git)

#### STREAM 3
  - [What is Git Flow | How to use Git Flow | Learn Git](https://www.gitkraken.com/learn/git/git-flow)
  - [gitkraken.com/wp-content/uploads/2021/03/git-flow-4.svg](https://www.gitkraken.com/wp-content/uploads/2021/03/git-flow-4.svg)
  - [A successful Git branching model » nvie.com](https://nvie.com/posts/a-successful-git-branching-model/)
  - [What is the best Git branch strategy? | Git Best Practices](https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy)
  - [GitHub flow - GitHub Docs](https://docs.github.com/en/get-started/quickstart/github-flow)

#### STREAM 4
  - [make a new repository by git by bash - Google Search](https://www.google.com/search?q=make+a+new+repository+by+git+by+bash&oq=make+a+new+repository+by+git+by+bash&aqs=chrome..69i57.850j0j7&client=ms-android-huawei-rev1&sourceid=chrome-mobile&ie=UTF-8)
  - [How to create a new repo at Github using git bash? - Stack Overflow](https://stackoverflow.com/questions/11693288/how-to-create-a-new-repo-at-github-using-git-bash)
  - [git - Add a new Project to GitHub via Bash command? - Stack Overflow](https://stackoverflow.com/questions/27456773/add-a-new-project-to-github-via-bash-command/27456812#27456812)
  - [git - Is it possible to create a remote repo on GitHub from the CLI without opening browser? - Stack Overflow](https://stackoverflow.com/questions/2423777/is-it-possible-to-create-a-remote-repo-on-github-from-the-cli-without-opening-br)
  - [curl/curl: A command line tool and library for transferring data with URL syntax, supporting DICT, FILE, FTP, FTPS, GOPHER, GOPHERS, HTTP, HTTPS, IMAP, etc.](https://github.com/curl/curl)
  - [curl](https://curl.se/)
  - [Install curl - Everything curl](https://everything.curl.dev/get)

#### STREAM 5
  - [Git and GitHub – Water Programming: A Collaborative Research Blog](https://waterprogramming.wordpress.com/category/programming/git-and-github/)

### Further Research -2 

Where is GIT located and what does it do internally?

#### Git On Your Computer
![screenshot 1663586197](https://user-images.githubusercontent.com/6398561/210326047-c7373563-ff1f-4433-b8b3-5e158aa9c62e.jpg)
![screenshot 1663586195](https://user-images.githubusercontent.com/6398561/210326049-c5adec77-9127-4165-a8d8-4f9f51213a2e.jpg)

#### Git-Internals
I have often contemplated how to fix this if the system fails?! So i looked up and found something know as Git Internals.


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
