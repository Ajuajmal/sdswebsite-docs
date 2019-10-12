[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[<img align="right" width="150" src="assets/join-slack-team.png">](https://studevsoc.slack.com/)


# First Contributions

It's hard. It's always hard the first time you do something. Especially when you are collaborating, making mistakes isn't a comfortable thing. We wanted to simplify the way new open-source contributors learn & contribute for the first time.

Reading articles & watching tutorials can help, but what's better than actually doing the stuff in a practice environment? This project aims at providing guidance & simplifying the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

#### *If you're not comfortable with command line, [here are tutorials using GUI tools.]( #tutorials-using-other-tools )*



<img align="right" width="300" src="./assets/fork.png" alt="fork this repository" />

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

`git clone "url you just copied"`

where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

`git clone https://github.com/studevsoc-sds/sdswebsite-docs.git`

**where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.**

## Create a branch

Change to the repository directory on your computer (if you are not already there):

`cd sdswebsite-docs/src/hf/`

Now create a branch using the `git checkout` command:

`git checkout -b <add-your-new-branch-name>`

For example:

`git checkout -b add-alonzo-church`

(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors-2k19.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

`git add Contributors.md`

Now commit those changes using the `git commit` command:

`git commit -m "Add <your-name> to Contributors list"`

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

`git push origin <add-your-branch-name>`

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats!  You just completed the standard _fork -> clone -> edit -> PR_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app]().

You could join our slack team in case you need any help or have any questions. [Join slack team](https://studevsoc.slack.com/).

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](#).

### [Additional material](additional-material/git_workflow_scenarios/additional-material.md)


## Tutorials Using Other Tools

[<img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100">](./github-desktop-tutorial.md)

[<img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100">](./github-windows-vs2017-tutorial.md)|<a href="gitkraken-tutorial.md"><img alt="GitKraken" src="/assets/gk-icon.png" width="100"></a>|<a href="github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width=100></a>|<a href="sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a>|
|---|---|---|---|---|
|[GitHub Desktop](github-desktop-tutorial.md)|[Visual Studio 2017](github-windows-vs2017-tutorial.md)|[GitKraken](gitkraken-tutorial.md)|[Visual Studio Code](github-windows-vs-code-tutorial.md)|[Atlassian Sourcetree](sourcetree-macos-tutorial.md)|

<br>

[<img width="185px" height="57px" src="assets/sds.png">](https://studevsoc.com)

[<img width="12px" height="12px" src="assets/copyleft.png"> First Contributions](https://github.com/firstcontributions/first-contributions)
