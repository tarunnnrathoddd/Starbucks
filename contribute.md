# Contribution Guidelines

Thank you for your interest in contributing to our project! Please follow these steps to make a meaningful contribution:

## How to Start Contributing?

1. Check the project's issues to see if the task you want to work on is already being discussed.

2. If the issue is not listed, create a new issue to describe what you plan to work on. Please provide a clear and detailed description of the issue.

3. Mention in the issue that you want to work on it to avoid duplication of efforts.

4. Wait for approval from the maintainers of this project before starting your work.

## Making Changes

5. Once your issue is approved, fork the repository.

6. Clone your forked repository to your local machine:

   ```bash
   git clone https://github.com/<your-github-username>/project-repo.git
   ```

7. Install any necessary dependencies by running else skip:

   ```bash
   npm install
   ```

8. To prevent merge conflicts, it's important to keep your forked repository in sync with the upstream (original) repository.:

   ```bash
   git remote add upstream https://github.com/original/repo.git
   git fetch upstream
   git pull upstream main
   ```

9. Create a new branch for your work:

   ```bash
   git checkout -b feature/your-feature
   ```

10. Make your changes and commit them with a descriptive commit message:

    ```bash
    git add .
    git commit -m "Add feature or fix issue #<issue-number>"
    ```

11. Push your changes to your forked repository:

    ```bash
    git push origin feature/your-feature
    ```

## Creating a Pull Request

12. Go to the GitHub page of your forked repository and click "New Pull Request."

13. Ensure the base repository is the original project repository and the base branch is the `main` branch.

14. In the pull request description, mention the issue number your pull request is related to, and provide any additional context if needed.

15. Submit the pull request.

## Review and Merge

16. Once you've submitted a pull request, be patient and wait for a project maintainer to review it. Be ready to make any required changes if requested.

17. Once your pull request is approved, it will be merged into the main project repository.

Thank you for your contribution!

## Note 🛑🛑🛑

- Create a new folder with the name of your component and add the HTML, CSS, and JavaScript files in that folder (don't add your component code to the index.html).
- Link the HTML file of your component to the link on the card created in the index.html file.
- Create new cards for each new component you make.
```

Make sure to replace `<your-github-username>`, `project-repo`, and `<issue-number>` with the appropriate values for your project. This `CONTRIBUTING.md` template provides clear instructions for contributors on how to get started, make changes, create pull requests, and more.
