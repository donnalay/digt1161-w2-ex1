# digt1161-w2-ex1

Exercise 1 — CLI Remote &amp; Local Basics

## CLI Reflection

#### Comparing the GitHub Desktop vs. CLI commit workflow

##### Github Desktop

- In the desktop app, the steps to commit files is a visual workflow.
- The GUI shows all of the information in one view for the user to confirm the changes, and provides UI components to input a commit title and description.
- Once they have commited their changes in the desktop application, the UI option to fetch/push in the top menu, updates to reflect that there is content that can be pushed to the remote.

##### CLI

- In the CLI, the user has to recall commands from memory, or look them up.
- The user can use git status to check the status of changes on their branch
- Once they have saved their changes in the IDE, they must use `git add <filename>` to "stage" the file to the branch.
- To commit their changes, they use command: `git commit -m "<commit description>"`
- Then, they use command: `git push origin main` to push their changes to the main branches, in the remote repository.
