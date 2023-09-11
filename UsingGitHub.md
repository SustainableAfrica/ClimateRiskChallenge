# Getting Started with GitHub: An Overview and Basics

GitHub is a powerful platform for version control and collaboration that plays a fundamental role in modern software development. It helps individuals and teams manage their code, track changes, and work together seamlessly. This tutorial will provide you with an overview of what GitHub is, how to get started with it, and some essential basics to help you get going.  

**Please Note:** Climate Challenge participants are **not required** to use GitHub.  It is intended to be a resource and allow access to AWS cloud resources.

## What is GitHub?

GitHub is a web-based platform that primarily serves as a hosting service for Git repositories. Git is a distributed version control system that allows developers to track changes in their code, collaborate with others, and manage different versions of their projects. GitHub enhances Git's functionality by providing a user-friendly web interface, social features, and tools for project management and collaboration.

**Watch this overview video** on how to use [Git/GitHub](https://www.youtube.com/watch?v=RGOj5yH7evk)

GitHub is widely used for:

1. **Code Hosting:** GitHub hosts millions of repositories, making it a central hub for open-source and private projects.

2. **Version Control:** It helps track changes in your codebase, allowing you to revert to previous versions, collaborate with others, and avoid conflicts.

3. **Collaboration:** Teams can work together efficiently, with features like pull requests, issue tracking, and code review tools.

4. **Project Management:** GitHub provides tools for organizing and managing projects, such as milestones, project boards, and automation workflows.

5. **Community and Open Source:** It fosters a community of developers, making it easy to discover, contribute to, and learn from open-source projects.

## Creating a GitHub Account

Before you can start using GitHub, you need to create an account. Follow these steps:

1. **Visit GitHub:** Go to [GitHub's website](https://github.com/) in your web browser.

2. **Sign Up:** Click on the "Sign Up" button, and you'll be prompted to enter your email address, create a password, and choose a username.

3. **Choose a Plan:** GitHub offers free plans for public repositories and paid plans for private repositories. Select the plan that suits your needs. Most beginners start with the free plan.

4. **Verify Your Email:** GitHub will send you a verification email. Open it and click the verification link to activate your account.

5. **Complete Your Profile:** Add a profile picture and some basic information to your GitHub profile to personalize it.

Now that you have a GitHub account, let's explore some essential GitHub basics.

## GitHub Basics

### Creating a Repository

A repository, often called a "repo," is where your project's files and code are stored. Each Climate Risk Research Challenge Team will be given a private repository to use and collaborate.  To create a new repository:

1. Log in to your GitHub account.

2. Click on the "+" sign in the top right corner and select "New repository."

3. Fill in the repository name, description, and other settings.

4. Choose between making the repository public (visible to everyone) or private (restricted access).

5. Click the "Create repository" button.

### Cloning a Repository

Cloning allows you to create a local copy of a GitHub repository on your computer. Use the following command in your terminal:

```bash
git clone <repository_url>
```
Replace <repository_url> with the URL of the GitHub repository you want to clone.

### Making Changes
Create or modify files in your local repository.

Use the following Git commands to track and commit changes:
```bash
git add .             # Add all changes to the staging area
git commit -m "Message describing the changes"
git push origin main  # Push changes to GitHub
```
### Pull Requests
When you want to contribute to someone else's repository or collaborate with team members, you can create a pull request (PR). Here's how:

1. Fork the repository on GitHub.

2. Clone your forked repository locally.

3. Make changes and commit them.

4. Create a new branch:
```bash
git checkout -b my-feature
```
5. Push the new branch to your GitHub repository:
```bash
git push origin my-feature
```
6. On GitHub, go to the original repository and create a pull request, selecting your branch.

7.  Describe your changes and submit the PR.

### Issues and Discussions
GitHub provides tools for issue tracking and discussions. You can report bugs, request features, or discuss any topic related to a repository.

1. To create an issue, go to the repository and click on the "Issues" tab. Click "New issue" and fill out the details.

2. To start a discussion, use the "Discussions" tab in the repository.

### Explore and Contribute
GitHub is a vast ecosystem of open-source projects. Explore repositories, contribute to projects you're interested in, and learn from other developers' code.

### Conclusion
GitHub is an indispensable tool for developers, whether you're working on personal projects, collaborating with a team, or contributing to open source. This tutorial covered the basics of what GitHub is, how to create an account, and some fundamental operations. As you continue to use GitHub, you'll discover more advanced features and best practices that can streamline your development workflow and foster collaboration.
