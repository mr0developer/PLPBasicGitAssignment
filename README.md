# PLPBasicGitAssignment
1. GitHub Repository Creation:

  - Log in to your GitHub account.

  - Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").

  - Initialize it with a README file.



Task 2: Local Setup

  - Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").
  - Open a terminal or command prompt and navigate to the created folder.
  - Initialize a new Git repository in your local folder.
  - Link your local repository to the GitHub repository you created in Task 1.

   ```

git remote add origin <repository-url>

   ```

   Replace `<repository-url>` with the actual URL of your GitHub repository.

Task 3: Making Changes
  - Inside your local folder, create a new text file (e.g., `hello.txt`).
  - Add a simple text message (e.g., "Hello, Git!").
  - Stage the changes.

   ```bash

   git add hello.txt

   ```

  - Commit the changes.

   ```bash

   git commit -m "Add hello.txt with a greeting"

   ```
Task 4: Pushing to GitHub
  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin main

   ```
Task 5: Verification
  - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.
