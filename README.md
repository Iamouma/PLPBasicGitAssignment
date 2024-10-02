# PLPBasicGitAssignment.

 Local Setup

 Local Folder Setup:

  - Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").

  - Open a terminal or command prompt and navigate to the created folder.



 Git Initialization:

  - Initialize a new Git repository in your local folder.



 Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Task 1.

   ```

git remote add origin <repository-url>

   ```

   Replace `<repository-url>` with the actual URL of your GitHub repository.



 Making Changes

 Create a File:

  - Inside your local folder, create a new text file (e.g., `hello.txt`).

  - Add a simple text message (e.g., "Hello, Git!").



 Committing Changes:

  - Stage the changes.

   ```bash

   git add hello.txt

   ```

  - Commit the changes.

   ```bash

   git commit -m "Add hello.txt with a greeting"

   ```



 Pushing to GitHub

 Pushing to GitHub:

  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin main

   ```

 Verification

 Verify on GitHub:

  - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.
