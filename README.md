# Introduction to GitHub Issues

GitHub Issues is a powerful tool for tracking tasks, bug reports, feature requests, and more. This guide will give you an introduction to GitHub Issues. Here is a nice quickstart guide on [GitHub Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/configuring-issues/quickstart).

## Table of Contents

- [What are GitHub Issues?](#what-are-github-issues)
- [Creating and Managing Issues](#creating-and-managing-issues)
- [Using Labels, Milestones, and Assignees](#using-labels-milestones-and-assignees)
- [Best Practices](#best-practices)
- [Linking Commits and Pull Requests](#linking-commits-and-pull-requests)

## What are GitHub Issues?

GitHub Issues are discussion threads that allow teams to track bugs, features, tasks, and any kind of project-related work. They provide a centralized place for collaboration, troubleshooting, and planning.

## Creating and Managing Issues

### Creating an Issue
1. Navigate to the **Issues** tab in your GitHub repository.
2. Click the **New Issue** button.
3. Fill in the **Title** and **Description** fields. Use Markdown to format your text, add links, images, and code snippets.
4. Click **Submit new issue** to create the issue.

### Commenting and Discussion
- **Discussion:** Once an issue is open, collaborators can comment to ask questions, share ideas, or propose solutions.
- **Mentions:** Use `@username` to notify specific team members.

### Editing and Updating
- You can update the title, description, and add comments at any time to reflect new information or progress.

## Using Labels, Milestones, and Assignees

- **Labels:** Apply labels to quickly categorize issues and filter them later. Check [this article](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels) that defines and introduces different types of labels.
- **Milestones:** Organize issues by milestones to track progress for each project phase. Check [this article](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/about-milestones) that talks more about milestones on GitHub Issues.
- **Assignees:** Assign an issue to a specific team member who will be responsible for resolving it. Check [this article](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/assigning-issues-and-pull-requests-to-other-github-users) that shows how to add assignees to your issue.

## Best Practices

- **Clear Titles and Descriptions:** Write concise and descriptive titles. Include enough detail in the description so others can understand the issue without needing to ask for more info.
- **Reproducible Steps:** For bug reports, list step-by-step instructions on how to reproduce the issue.
- **Visual Aids:** Use screenshots, GIFs, or code blocks to provide context and clarity.
- **Prioritization:** Use labels to classify issues (e.g., bug, enhancement, question) and assign them to team members as needed.
- **Milestones:** Group related issues under a milestone to track progress towards a specific release or goal. It is recommended that you create milestones (on GitHub issues) for this class.

## Linking Commits and Pull Requests

- **Cross-Referencing:** Mention issue numbers in commit messages or pull request descriptions to create links between the discussions and the code changes.
- **Automatic Closure:** Use keywords in your commit messages to automatically close issues. For instance, merging a commit that includes the message `Fix #123` will automatically close the corresponding issue (`#123`).