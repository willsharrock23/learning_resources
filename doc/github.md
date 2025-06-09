# GitHub

GitHub is a web-based platform for storing, sharing and collaboration on code-based projects. It is great for tracking changes made to code, sharing ideas and scrum-based planning.

## Learn GitHub

- [GitHub Skills](https://github.com/skills): GitHub's own how-to-use guide.
- [IBM GitHub Starter Course](https://www.coursera.org/learn/getting-started-with-git-and-github): If you have a coursera subscription (or can get one) then this online course is useful for getting started, or to solidify existing knowledge. It is coherent and explains all concepts in full, with some small GitHub based projects for practice.
- [Udemy Full-Stack Dev Course](https://www.udemy.com/course/the-complete-web-development-bootcamp/): Use section 27 only. In my opinion, this is the best video tutorial on GitHub. For access see Will Sharrock.

## GitHub Tools

If working on a project on GitHub you will ideally need a desktop tool for interacting with the repositories and collaborating. 

- [GitKraken](https://www.gitkraken.com/) is my personal favourite. It works well with VSCode, and the UI is intuitive. This tool in particular makes committing, stashing, rebasing and pulling relatively simple compared to other tools.

- Another option is [GitHub Desktop](https://desktop.github.com/download/). For the most common and simplest Git commands, such as commit, branch, checkout, pull, push, or merge, GitHub Desktop does pretty well. But once you start working with multiple branches and more complex workflows GitHub Desktop requires you to keep a lot of things organized in your head as you are working and is not much help in those areas. So for small projects this will suffice.

## GitHub in a pipeline

GitHub is also a Continuous Integration (CI) tool. [GitHub Actions](https://github.com/features/actions) enables automation of software workflows via yml files. Visit the [Actions marketpalce](https://github.com/marketplace?type=actions). You will probably find that if you want to automate a process in GitHub then somebody else has already done that. You can of course write your own actions:

- Here is a [guide on writing GH Actions](https://docs.github.com/en/actions/writing-workflows/quickstart)
- Here is a [guide on building a CI/CD pipeline using GH Actions.](https://github.blog/enterprise-software/ci-cd/build-ci-cd-pipeline-github-actions-four-steps/)

Some example actions that I find useful:

- [Create new Semantic Version](https://github.com/marketplace/actions/create-new-semantic-version)
- [Checkout](https://github.com/marketplace/actions/checkout)
- [Check signed commits in PR](https://github.com/marketplace/actions/check-signed-commits-in-pr)
- [Release Action](https://github.com/marketplace/actions/create-release)
- [Build and push Docker images](https://github.com/marketplace/actions/build-and-push-docker-images)

## GitHub Authentication

Here is the documentation for [GitHub Authentication](https://docs.github.com/en/authentication).
This will come in handy when automating the workflow from development to a staging or production environment. The documentation covers Personal Access Tokens, SSH and how to verify your commit signatures.

## GitHub Project

It is a good idea to start a project in GitHub. This allows for funnelling issues into an ordered, prioritised list with milestones.

For teams using Scrum, you can use a [kanban board](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/customizing-the-board-layout) project template.

Here is the [GitHub Projects documentation](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) to help get started.