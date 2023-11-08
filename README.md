# To Do

1. Create a new directory for your project

    `mkdir new-project`

2. Navigate into the newly created project directory

    `cd new-project`

3. Initialize a new Git repository in the project directory

    `git init`

4. Add a remote Git repository as the origin for your project. Replace `<url>` with the actual URL

    `git remote add origin <url>`

5. Push your local repository to the remote repository's main branch

    `git push -u origin main`

6. Create a README file with the initial content for your project

    `echo "# new-project" > README.md`

7. Add the README file to the staging area for the next commit

    `git add README.md`

8. Commit the changes you made, initializing the project

    `git commit -m "init"`

9. Create and switch to a new Git branch for making changes

    `git checkout -b development`

10. Add the README file again to the staging area for the new branch

    `git add README.md`

11. Commit the changes on the new branch with a message

    `git commit -m "add instruction"`

12. Switch back to the main branch

    `git checkout main`

13. Merge the changes from the new branch into the main branch

    `git merge`

14. Check the status of your Git repository

    `git status`

15. Push the changes you made on the main branch to the remote repository

    `git push origin main`
