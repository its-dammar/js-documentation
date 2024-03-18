

- To Added new project on the gitHub
    1. git init                                  : initialize git on the project
    2. git add .                                 : add all folders and files
    3. git commit -m "This is first commit"
        - Please tell me who you are.
            - git config --global user.email "www.yuv901@gmail.com"
            - git config --global user.name "YuvrajPun"
    4. git branch -M main                        : Modify the branch name master to main
    5. git remote add origin main peste_link
        - git remote add origin https://github.com/YuvrajPun/js-documentation.git
    6. git push -u origin main


- To update the project
    - git add .
    - git commit -m "modify the gitCommand file"
    - git pull 
    - git push origin main

- To clone the project (download)
    - git clone link


- To check the branch 
    - git branch

-To remove the modification
    - git stash


Git commit message:

| Type            | Description                                               | Example Commit Message                                    |
|-----------------|-----------------------------------------------------------|-----------------------------------------------------------|
| `feat`          | Introduces a new feature.                                 | `feat: add user profile page`                             |
| `fix`           | Patches a bug.                                            | `fix: correct email validation logic`                     |
| `docs`          | Documentation only changes.                               | `docs: update README with new installation instructions`  |
| `style`         | Changes that do not affect the meaning of the code.      | `style: format CSS files`                                  |
| `refactor`      | A code change that neither fixes a bug nor adds a feature.| `refactor: streamline data parsing functions`             |
| `perf`          | Improves performance.                                     | `perf: optimize database query`                           |
| `test`          | Adding missing tests or correcting existing tests.       | `test: add unit tests for user service`                    |
| `chore`         | Changes to the build process or auxiliary tools.         | `chore: update npm dependencies`                           |
| `ci`            | Changes to CI configuration files and scripts.           | `ci: add GitHub Actions workflow for CI`                   |
| `build`         | Affects the build system or external dependencies.       | `build: upgrade to webpack 5`                              |
| `temp`          | Temporary commit that won't be included in the changelog.| `temp: work in progress on new feature`                    |
| `i18n`/`l10n`   | Internationalization and localization changes.           | `i18n: add Spanish translations`                           |
| `security`      | Addresses security vulnerabilities or improvements.      | `security: fix SQL injection vulnerability`                |
| `deprecate`     | Marks features or code for future removal.               | `deprecate: mark old authentication method as deprecated`  |
| `accessibility` | Improvements or fixes related to accessibility.          | `accessibility: improve form labels for screen readers`    |
| `config`        | Changes to configuration files.                          | `config: update .eslintrc rules`                           |



Git command list with description:
| Category          | Command                   | Description                                                           |
|-------------------|---------------------------|-----------------------------------------------------------------------|
| Setup & Config    | `git config`              | Configure user information, preferences, etc.                         |
|                   | `git init`                | Initialize a new Git repository.                                      |
|                   | `git clone [url]`         | Clone a repository into a new directory.                              |
| Basic Snapshotting| `git add [file]`          | Add file contents to the index.                                       |
|                   | `git status`              | Show the working tree status.                                         |
|                   | `git commit`              | Record changes to the repository.                                     |
|                   | `git rm [file]`           | Remove files from the working tree and from the index.                |
|                   | `git mv [file]`           | Move or rename a file, a directory, or a symlink.                     |
| Branching & Merging | `git branch`            | List, create, or delete branches.                                     |
|                   | `git checkout [branch]`   | Switch branches or restore working tree files.                        |
|                   | `git merge [branch]`      | Join two or more development histories together.                      |
|                   | `git tag [tag]`           | Create, list, delete or verify a tag object signed with GPG.          |
| Sharing & Updating | `git fetch [alias]`      | Download objects and refs from another repository.                    |
|                   | `git pull [alias]`        | Fetch from and integrate with another repository or a local branch.  |
|                   | `git push [alias] [branch]` | Update remote refs along with associated objects.                 |
| Inspection & Comparison | `git log`           | Show commit logs.                                                     |
|                   | `git diff`                | Show changes between commits, commit and working tree, etc.           |
|                   | `git show [commit]`       | Show various types of objects.                                        |
|                   | `git status`              | Show the working tree status.                                         |
| Stashing & Cleaning | `git stash`             | Stash the changes in a dirty working directory away.                  |
|                   | `git clean`               | Remove untracked files from the working tree.                         |


Git command list with description and examples: 

| Category            | Command                     | Description                                                           | Example                                  |
|---------------------|-----------------------------|-----------------------------------------------------------------------|------------------------------------------|
| Setup & Config      | `git config`                | Configure user information, preferences, etc.                         | `git config --global user.name "John Doe"` |
|                     | `git init`                  | Initialize a new Git repository.                                      | `git init`                               |
|                     | `git clone [url]`           | Clone a repository into a new directory.                              | `git clone https://github.com/example/repo.git` |
| Basic Snapshotting  | `git add [file]`            | Add file contents to the index.                                       | `git add .`                              |
|                     | `git status`                | Show the working tree status.                                         | `git status`                             |
|                     | `git commit`                | Record changes to the repository.                                     | `git commit -m "Initial commit"`         |
|                     | `git rm [file]`             | Remove files from the working tree and from the index.                | `git rm file.txt`                        |
|                     | `git mv [file]`             | Move or rename a file, a directory, or a symlink.                     | `git mv file.txt dir/file.txt`           |
| Branching & Merging | `git branch`                | List, create, or delete branches.                                     | `git branch -a`                          |
|                     | `git checkout [branch]`     | Switch branches or restore working tree files.                        | `git checkout develop`                   |
|                     | `git merge [branch]`        | Join two or more development histories together.                      | `git merge feature/new-feature`          |
|                     | `git tag [tag]`             | Create, list, delete or verify a tag object signed with GPG.          | `git tag v1.0.0`                         |
| Sharing & Updating  | `git fetch [alias]`         | Download objects and refs from another repository.                    | `git fetch origin`                       |
|                     | `git pull [alias]`          | Fetch from and integrate with another repository or a local branch.   | `git pull origin master`                 |
|                     | `git push [alias] [branch]` | Update remote refs along with associated objects.                     | `git push origin master`                 |
| Inspection & Comparison | `git log`               | Show commit logs.                                                     | `git log`                                |
|                     | `git diff`                  | Show changes between commits, commit and working tree, etc.           | `git diff HEAD~1`                        |
|                     | `git show [commit]`         | Show various types of objects.                                        | `git show abc1234`                       |
|                     | `git status`                | Show the working tree status (duplicated for emphasis).               | `git status`                             |
| Stashing & Cleaning | `git stash`                 | Stash the changes in a dirty working directory away.                  | `git stash push -m "Work in progress"`   |
|                     | `git clean`                 | Remove untracked files from the working tree.                         | `git clean -f`                           |
