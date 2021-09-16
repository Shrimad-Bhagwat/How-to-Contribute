# How-to-Contribute
```
This repository will help you to learn about How to Contribute by adding your name in the Contributors.md file.

```
## Follow these steps
   1. [Fork this repository](#1-fork-this-repository)
   2. [Clone the repository](#2-clone-the-repository)
   3. [Create a branch](#3-create-a-branch)
   4. [Make necessary changes and commit those changes](#4-make-necessary-changes-and-commit-those-changes)
   5. [Push changes to GitHub](#5-push-changes-to-github)
   6. [Submit your changes for review](#6-submit-your-changes-for-review)

---


## 1. Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## 2. Clone the repository

<img align="right" width="300" src="https://github.com/Shrimad-Bhagwat/How-to-Contribute/blob/main/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://github.com/Shrimad-Bhagwat/How-to-Contribute/blob/main/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
https://github.com/this-is-you/How-to-Contribute.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## 3. Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd How-to-Contribute
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-shrimad-bhagwat
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## 4. Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## 5. Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## 6. Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://github.com/Shrimad-Bhagwat/How-to-Contribute/blob/main/assets/Readme/pull-request.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://github.com/Shrimad-Bhagwat/How-to-Contribute/blob/main/assets/Readme/create-pr.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
