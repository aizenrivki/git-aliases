# Git Aliases Examples

Welcome to the repository where I share the Git aliases I find useful in my daily development workflow. Git aliases are custom shortcuts that make Git commands more efficient and help streamline common tasks. Feel free to explore these aliases and use them to simplify your Git experience.

## How to Use

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/aizenrivki/git-aliases.git
   ```

2. Navigate to the repository directory:

   ```shell
   cd git-aliases
   ```

3. Open the .gitconfig file in this repository:

   ```shell
   cat .gitconfig
   ```

4. Copy the content of the [alias] section and paste it into your own `.gitconfig` file, which is usually located in your home directory.

5. Save your `.gitconfig` file.
6. Open your `.gitconfig` file and replace occurrences of 'master' with 'main' if your default branch is 'main'. For example, if you have:

   ```ini
   rs = reset --soft origin/master
   ```

    You can change it to:

    ```ini
    rs = reset --soft origin/main
    ```

7. You can now use these aliases in your Git commands. For example:

   ```shell
   git alias-name
   ```

## Aliases

- `la`: List all aliases.
- `rs`: Soft reset to origin/master.
- `rh`: Hard reset to origin/master.
- `st`: List uncommitted changes in a compact format
- `lg`: View the Git Log
- `add-commit`: Shortcut for Git Add all tracked files and Commit
- `branch-list`: List all local branches.
- `branch-local-list`: List Local Branches Not in Remote
- `branch-local-delete`: Delete Local Branches Not in Remote
- `fetch-master`: Update the Local master Branch
- `checkout-branch`: Create a New Branch from master
- `assume`: Ignore Changes in a File (Assume Unchanged)
- `unassume`: Stop Ignoring Changes in a File
- `assumed`: List Assumed (Ignored) Files
- `unassumeall`: Stop Ignoring All Assumed (Ignored) Files
- `assumeall`: Ignore All Modified Files
- `rebase-current`: Rebase Current Branch on master
- `pr`: Create a Draft Pull Request

You can also check out my Medium article where I discuss few of these aliases in more detail: [Streamlining Your Git Workflow: Common Git Aliases You Need to Know](https://medium.com/@rivkiaizen/streamlining-your-git-workflow-common-git-aliases-you-need-to-know-e6411573fade).

Feel free to explore the aliases, and if you have any of your own to share or suggestions for improvements, please open an issue or submit a pull request. Let's make Git even more efficient together!

## License

This repository is licensed under the MIT License - see the LICENSE file for details.
