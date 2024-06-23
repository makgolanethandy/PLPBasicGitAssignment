 Task 1: Repository Setup
  - Log into GitHub account.
  - Create a new repository "PLPBasicGitAssignment" on GitHub
  - Initialize it with a README file.

2. Local Folder Setup:
  - Open Gitbash
  - Go to your computer drive of choice
    * cd c:/
  - Create a folder name "PLPBasicGitAssignment"
    * mkdir PLPBasicGitAssignment
  - Navigate to the created folder
    * cd PLPBasicGitAssignment

3. Initialize a new Git repository in your local folder.
  - git init

4. Link your local repository to the GitHub repository you created in Task 1.
  - git remote add origin https://github.com/makgolanethandy/PLPBasicGitAssignment.git

5. Create a new text file (e.g., `hello.txt`) and add a simple text message (e.g., "Hello, Git!").
  - touch hello.txt
  - echo "Hello, Git"> hello.txt
*Verify that the text were committed
  - cat hello.txt

6. Committing Changes
  - git add hello.txt
  - git commit -m "Add hello.txt with a greeting"

7. Pushing to GitHub
  - git push -u origin master
8. Verify changes on github repository created in TASK 1.
