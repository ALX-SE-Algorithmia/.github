## Collaborating on our open source projects
You can hop on to collaborate on our open-source projects using the "fork and branch" workflow. It involves the folowing steps:

1. **Create an issue on GitHub**: Create an issue in the GitHub repository of the project you would like to contribute to. Use the featured templares, and do well to tag the <a href="https://github.com/orgs/ALX-SE-Algorithmia/teams/code-reviewing-team">Code Review Team</a> in your issue.

2. **Fork the Repository:** Start by navigating to the repository on the platform where it is hosted (e.g., GitHub) and click on the "Fork" button. This creates a copy of the repository under your GitHub account.

3. **Clone the Forked Repository:** Once you have forked the repository, clone it to your local machine using the `git clone` command. This creates a local copy of the repository that you can work with.

4. **Add the Original Repository as a Remote:** To keep your forked repository in sync with the original repository, you need to add the original repository as a remote. Navigate to the cloned repository on your local machine using the `cd` command, and then add the remote using the `git remote` command:
   ```
   cd <cloned-repo-folder>
   git remote add upstream <original-repo-url>
   ```

5. **Switch to the New Branch:** Switch to the newly created branch using the `git checkout` command:
   ```
   git checkout <branch-name>
   ```

6. **Make Changes and Commit:** Make the necessary changes to the codebase in your local repository. Once you have made the desired changes, stage the changes using `git add` and commit them using `git commit`:
   ```
   git add .
   git commit -m "Descriptive commit message"
   ```

7. **Push Changes to Your Fork:** Push the changes from your local branch to your forked repository on the remote server:
   ```
   git push origin <branch-name>
   ```

8. **Create a Pull Request:** Go to your forked repository on the hosting platform (e.g., GitHub), switch to the branch you just pushed, and click on the "New Pull Request" button. This will allow you to submit your changes to the original repository for review.

9. **Syncing with the Original Repository:** Periodically, you may want to sync your forked repository with the changes made in the original repository. To do this, fetch the changes from the original repository using the remote you added earlier and then merge those changes into your local branch:
   ```
   git fetch upstream
   git merge upstream/main  # or upstream/master for older conventions
   ```
