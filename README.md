## Homework: GitHub Fundamentals

### Required Files 

- Ansible YAML scripts from the week on cloud security.
    - Gather all of your Ansible YAML scripts from your Ansible container on your jump box.
    - Copy and paste these into new documents on your local machine.
- Bash scripts from the week on Linux.
    - Gather all of your system configuration scripts you created during the weeks on Linux.
- Network diagrams.
    - Gather all of the network diagrams you created during the weeks on cloud security and networking. 

### Your Goals

1. Create a GitHub repository for all of your files. 

2. Copy all of your files into the repository and create a README explaining the repository.

### Topics Covered in this Assignment
The topics covered in this homework assignment are:

- Creating a new GitHub repository.
- Syncing a local repository.
- Creating a README file.
- [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- The following commands:
    - `git pull`
    - `git add`
    - `git commit -m`
    - `git push origin --set-upstream <-branch->`

---

### Instructions
1. Create your GitHub repository.
    - Go to [github.com](https://github.com/) and sign up for GitHub.
    - Confirm your email address.
    - Click **Create a Repository**.
    - Name your repository and give it a short description.
    - Check the box for **Initialize this repository with a README**.
    - Click **Create Repository**. 

2. Download your repository. 

    - Click the green **Clone or Download** button on the right side.
    - Copy the link.
    - Go to your command line and run the command: `git clone https://github.com/your-username/yourlink.git`
        - Enter your GitHub username and password to complete the download.

3. Once you have the repository downloaded, copy your scripts and diagrams into it. 
    - Create folders for `Linux`, `Ansible` and `Diagrams`.
    - Copy your scripts and diagrams to the appropriate folder.

4. Sync your local and remote repositories. 
    - In your terminal, make sure you're located in the top directory of your repo.  

    - Run `git add .` to specify that you want to sync _all_ the items and directories that you just added to your repo. This command stages your files for a commit. 

    - Run the command `git commit -m "First commit"` to confirm the commit and add a note describing it ("First commit").  

     - Run `git push` to finalize the sync.

    - Go to github.com and confirm your content is there.

5. Add the README file you created during Day 3 of the project week.
    - Click on the `README.md` file in your GitHub repo.
    - Click on the small pencil that reads **Edit this file** on hover.
    - Copy and paste the `README.md` file you wrote during class. 
    - Make any desired changes and click **Commit Changes** at the bottom of the screen.

     **Note:** READMEs are written in Markdown. This [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) has more information about writing in Markdown. 
     
Check your repo for any errors or typos. You now have a GitHub repository that is ready to present and share with the world. 
    
--- 
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.




