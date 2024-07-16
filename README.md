# PLPBasicGitAssignment
# Step-by-Step Guide to Creating and Managing a GitHub Repository
1. Create a GitHub Repository
* Visited GitHub website and logged into my account.
* Clicked on the "+" icon at the top right corner and selected "New repository".
* Filled in the repository name PLPBasicGitAssignment, added a description, and choose to initialize the repository with a README.
Click "Create repository".

2. Navigated to the Local folder
Changed to the directory of the local folder:
>>> cd PLPBasicGitAssignment

Initialize the repository:
>>> git init

3. Created a New File and Edited It
Created a new file called hello.txt:
>>> touch hello.txt
>>> echo  "Hello, Git!">>hello.txt

4. Added the New File to the Staging Area
>>> git add hello.txt

7. Commited the Changes
>>> git commit -m "Add hello.txt with greetings"

8. Pushed the Changes to the Remote Repository
>>> git remote add origin https://github.com/EmanuelSolver/PLPBasicGitAssignment.git
>>> git push -u origin main