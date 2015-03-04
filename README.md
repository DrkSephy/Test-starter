Django-Hackathon-Starter
========================

Django starter project for hackathons. Features to include are:

* OAuth strategy for multiple providers, such as Google+, Twitter, Facebook.
* User system up and running from the start.
* Template chooser

#### Contributing

In order to contribute to this project, please follow the steps outlined below:

1. [https://help.github.com/articles/fork-a-repo/](fork) the project, clone your fork and configure the remotes:

    # Clone your fork of the repo into the current directory
    git clone git@github.com:<YOUR_USERNAME>/Django-Hackathon-Starter.git

    # Navigate to the newly cloned directory in your terminal
    cd Django-Hackathon-Starter

    # Assign the original repo to a remote called "upstream"
    git remote add upstream https://github.com/DrkSephy/Django-Hackathon-Starter.git

The link above which demonstrates how to fork goes in-depth on how to set up your remotes. This is necessary so that you can pull any changes from the master repository (mine) into your forked repository. 

2. To fetch changes from the master repository (mine) to your cloned copy on your machine:

    # Switch to the master branch
    git checkout master

    # Fetch latest changes
    git pull upstream master


3. On your local clone, create a new branch called `dev`:

    git checkout -b dev

We will be using a `dev` branch for experimental changes. Whenever these changes are stable, they will be merged into the `master` branch, in order to ensure our project is always in a working state. 

4. Whenever you do changes, make sure you commit and push them to the `dev` branch, **not** the master branch. When you are ready to send a pull request, follow the [https://help.github.com/articles/using-pull-requests/](instructions here). In this case, you will send a pull request from your `dev` branch to my `dev` branch.



