# Forking a repository

<h2>Step-1</h2>
Click Fork

<h2>Step-2</h2>
Select an owner for the forked repository.
<h2>Step-3</h2>
By default, forks are named the same as their upstream repositories. You can change the name of the fork to distinguish it further.
<h2>Step-4</h2>
Choose whether to copy only the default branch or all branches to the new fork. For many forking scenarios, such as contributing to open-source projects, you only need to copy the default branch. By default, only the default branch is copied.
<h2>Step-5</h2>
Click Create fork.

# Creating a branch to work on
git branch BRANCH-NAME
<br>git checkout BRANCH-NAME
# Making and pushing changes
git add .

<br>git commit -m "a short description of the change"

<br>git push
# Making a pull request
At last, you're ready to propose changes into the main project! This is the final step in producing a fork of someone else's project, and arguably the most important. If you've made a change that you feel would benefit the community as a whole, you should definitely consider contributing back.

To do so, head on over to the repository on GitHub where your project lives. For this example, it would be at https://github.com/<your_username>/Spoon-Knife. You'll see a banner indicating that your branch is one commit ahead of octocat:main. Click Contribute and then Open a pull request.

GitHub will bring you to a page that shows the differences between your fork and the octocat/Spoon-Knife repository. Click Create pull request.

GitHub will bring you to a page where you can enter a title and a description of your changes. It's important to provide as much useful information and a rationale for why you're making this pull request in the first place. The project owner needs to be able to determine whether your change is as useful to everyone as you think it is. Finally, click Create pull request.
