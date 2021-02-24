# Group Git

![](https://assets.t3n.sc/news/wp-content/uploads/2018/07/git-branch-workflow-collaboration-1.jpg?auto=compress%2Cformat&fit=crop&fm=jpg&h=630&ixlib=php-1.1.0&q=65&w=1200&s=4cc20451bf278e271210ea8bb2699397)


## Overview
In this exercise, we'll practice collaborating effectively as a team with git workflows. 

## Getting Started
- `Clone` this repository DO NOT `fork` it 

## Instructions
### Git Collaboration
One of the main advantages of being comfortable with `git` is that it allows you the ability to collaborate with teams through organizations and shared repositories hosted here on `Github`. `Git` is a language used for **Version Control**, which allows us to save _versioned_ copies of our project codebases as we add to them.  Typically, we'll store these codebases on here on `Github`. However, `git` also allows for collaboration.

Take a second to think about how we've been receiving and submitting homework in this course. 
- Forking and cloning a repository
- Adding changes and commiting them
- Pushing to our forked remote repository
- Finally, making a pull request on the main repository with our changes

In actuality, we've been doing `git collaboration` all along! In the case of our homework, we've been using the `fork and pull request` method of collaboration.

We'll be using the shared repository `feature branch` method of collaboration in this course. While this is the way we'll be collaborating in this course, there are other methods out there. Think of this method as our organization's style guide for collaboration.
___

### Feature Branch Workflow
 
![](https://zepel.io/blog/content/images/2020/05/Feature-Branch-git-workflow-4.png)

With a [feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow), we'll be sharing a single repository with a main branch and doing our work in separate branches before merging it into the main branch of the project. To create our own, separate branches for the project, we'll be using this command:

```sh
git checkout -b your-branch-name
```

> The -b flag tells the checkout command to create a new branch if one with that name doesn't already exist

Let's take 5 minutes to read about [Checkout](https://www.atlassian.com/git/tutorials/using-branches/git-checkout).



