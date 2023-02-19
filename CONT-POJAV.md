# Contributing to PojavLauncher itself 

Thank you for your interest in out project! The biggest advantage of a software being open-source is that everyone can contribute and help us improve the launcher.

There are 2 main ways to contribute:

### The easiest method: GitHub website

On a PC, go to the main repository for [Android](https://github.com/PojavLauncherTeam/PojavLauncher) or [iOS](https://github.com/PojavLauncherTeam/PojavLauncher_iOS). Click on the `Fork` button. A prompt will appear, allowing you to change the repository name and description. Click on `Create fork` when you are ready.

Now you are free to modify the code. You can explore the repository tree, add or remove files, change its content...

After you are done, go to the `Code` tab of your repository, then click `Open pull request`.

The `Open a pull request` page will guide you to create a pull request. The last step is click on `Create pull request`. PojavLauncherTeam will review your code and merge it into the repository.

### The fast method: command line utilities

1. Follow these guides to install [GitHub CLI](https://cli.github.com/manual/installation) and [`git`](https://github.com/git-guides/install-git) to your PC.

2. Execute
```
gh auth login
```
to link your account to the GitHub CLI.

3. Start forking the repository:
```
git clone https://github.com/PojavLauncherTeam/PojavLauncher
```
(for Android)
```
git clone https://github.com/PojavLauncherTeam/PojavLauncher_iOS
```
(for iOS)

4. Change directory to the cloned repository, and modify the code as you want.

❗ *If you want to remove files, use `git rm <file>`.*

5. Save changes:
```
git add --all
git commit -m <commit_message>
```

If you want to know which changes you have made so far, use `git status` before committing.

6. Send pull request to GitHub:
```
gh pr create
```
