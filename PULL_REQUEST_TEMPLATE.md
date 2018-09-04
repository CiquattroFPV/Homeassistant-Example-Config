Submit your work

Submit your improvements, fixes, and new features to Homeassistant-Example-Config one at a time, using GitHub Pull Requests. Here are the steps:

    From your fork's dev branch, create a new branch to hold your changes:

    git checkout -b some-feature

    Make your changes, create a new platform, develop a new component, or fix issues.

    Test your changes and check for style violations.

    If everything looks good according to these musts, commit your changes:

    git add .

    git commit -m "Added some-feature"
        Write a meaningful commit message and not only Update or Fix.
        Use a capital letter to start with your commit message.
        Don't prefix your commit message with [bla.bla] or platform:.
        Consider adding tests to ensure that your code works.

    Push your committed changes back to your fork on GitHub:

    git push origin HEAD

    Follow these steps to create your pull request.
        On GitHub, navigate to the main page of the Home Assistant repository.
        In the "Branch" menu, choose the branch that contains your commits (from your fork).
        To the right of the Branch menu, click New pull request.
        Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made your changes in. Make sure the Home Assistant branch matches with your forked branch (dev) else you will propose ALL commits between branches.
        Type a title and complete the provided description for your pull request.
        Click Create pull request.

    Check for comments and suggestions on your pull request and keep an eye on the CI output.

