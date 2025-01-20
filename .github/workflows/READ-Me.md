Here's what the entries in the welcome.yml file, on the welcome-workflow branch, mean:

name: Post welcome comment gives your workflow a name. This name will appear in the Actions tab of your repository.

on: pull_request: types: [opened] indicates that your workflow will execute whenever someone opens a pull request in your repository.
permissions assigns the workflow permissions to operate on the repository

pull-requests: write gives the workflow permission to write to pull requests. This is needed to create the welcome comment.

Next, we need to specify jobs to run.
