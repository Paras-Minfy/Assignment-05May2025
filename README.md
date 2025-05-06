# Git Fundamentals & GitHub Collaboration

## Assignment 1: Fundamental Git Commands and Workflow

### Objective
Learn fundamental Git commands and their basic workflow.

### Explanation of Git Commands

1. **Initialize a Local Git Repository**  
   - Used `git init` to initialize an empty Git repository in the project directory.  
   - This creates a `.git` folder, allowing version control for the files in the directory.

2. **Create and Add a File to Staging**  
   - Created `simple.txt` using `touch simple.txt`.  
   - Added initial content to the file and staged it with `git add .`.  
   - Committed the changes using `git commit -m "Asssesment 1 Initial Commit"`, creating the first commit in the repository.

3. **Making Changes and Committing Updates**  
   - **First Change:** Updated the content to include a submission deadline.  
     - Staged and committed with `git commit -m "A1 - Change 1"`.  
   - **Second Change:** Added information about the continuity of assessments.  
     - Staged and committed with `git commit -m "A1 - Change 2"`.  
   - **Third Change:** Added details about the third assessment being in a different repository.  
     - Staged and committed with `git commit -m "A1 - Change 3"`.  

4. **Viewing Commit History**  
   - Used `git log --oneline --graph` to display a concise history of commits.   

5. **Examining Differences Between Commits**  
   - Used `git diff HEAD~1 HEAD` to compare the latest commit with the previous one.  

6. **Git Branches**
   - ![Git A1 Branches](https://github.com/Paras-Minfy/Assignment-05May2025/blob/main/Screenshots/Assignment1GraphSS.png)

7. **Git Commands Screenshots**
   - ![Git Commands Screenshots](https://github.com/Paras-Minfy/Assignment-05May2025/blob/main/Screenshots/Assignment1SS.png)

---

## Assignment 2: GitHub Basics & Collaboration

### Explanation of GitHub Commands

1. **Push Repository to GitHub**  
   - Added a remote repository using `git remote add origin https://github.com/Paras-Minfy/Assignment-05May2025`.  
   - Set the main branch using `git branch -M main`.  
   - Pushed changes to GitHub with `git push -u origin main`.  

2. **Pull Changes from GitHub**  
   - Used `git pull origin main` to ensure the local repository is in sync with GitHub.
   - ![Assignment2SSp1](https://github.com/Paras-Minfy/Assignment-1-and-2/blob/main/Screenshots/Assignment2SSp1.png)
   - ![Assignment2SSp2](https://github.com/Paras-Minfy/Assignment-1-and-2/blob/main/Screenshots/Assignment2SSp2.png)

3. **Create and Work on a New Branch**  
   - Created a branch for updating the README file using `git branch feature/update-readme`.  
   - Switched to the new branch using `git checkout feature/update-readme`.  
   - Made changes and committed them with `git commit -m "A2 - Change README.md"`.  
   - Pushed changes to GitHub using `git push origin feature/update-readme`.  

4. **Creating a Pull Request and Merging**  
   - Opened a pull request from `feature/update-readme` to `main` on GitHub.  
   - Reviewed and merged the pull request.  
   ![Git A2 Graph Screenshot](https://github.com/Paras-Minfy/Assignment-05May2025/blob/main/Screenshots/Assignment2GraphSS.png)

---

## Deliverables

- **Link to GitHub Repository**
=> [GitHub Repository](https://github.com/Paras-Minfy)

- **Pull Request Merge**  
  ![Pull Request Merge Screenshot](https://github.com/Paras-Minfy/Assignment-05May2025/blob/main/Screenshots/PullRequest.png)
