# How to Git: A workshop

## Summary

This workshop aims to teach you how to use Git + GitHub/GitLab in an efficient manor. It does not go too far into how you should do branching in your project, but is a beginner's guide to the powerful version control system that is Git. Nevertheless, you'll be taught to create feature branches, [which is a powerful way to work with Git](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).

There are a few differences between GitHub and GitLab, however this guide hopefully won't stumble upon too many of them. Differences I've found are:

| GitHub | GitLab |
| --- | --- |
| pull request | merge request |

For tooling you'll need nothing but a command line and a text editor, however a text editor with Git support will help you quite a bit. I prefer VS Code, especially for the built-in Git support and since the code in this repository is written in JavaScript.

## 0: Setup

1. If you haven't already, [download and install Git](https://git-scm.com/downloads).
2. In order to fork this project and push code to a repository on GitHub, you'll need a user account. Either sign in or create a new user.
3. You'll also need to have Node and npm (or yarn) installed. Go to [https://nodejs.org/en/download/](https://nodejs.org/en/download/) if you haven't already installed it.

## 1: Creating your own repository

1. In the top right corner of [this web site](https://github.com/boyum/git-workshop), click the Fork button to copy this project to your own account. When you fork a project, you create your very own branch that can be merged into the root repository, or any forked version of it.
2. Download the project to your pc by running `git clone https://github.com/<your username>/git-workshop` in a shell. This command will create a new directory where you're standing.

## 2: A brief introduction to Vue

Vue is a comfortable JavaScript framework that is easy to use and very performant. `.vue` files contain HTML markup, CSS stylesheets and JS logic, in some ways like React + JSX + styled-components. It's perfect for prototyping and doing small things, and at the same time, together with the state container VueX, it can work really well for larger applications as well.

### Task

1. Run `npm install` in order to install the project's dependencies.
2. Run `npm run serve` to start a development server on [http://localhost:8080/](http://localhost:8080/).

## 3: Fixing bugs

## Project setup

```shell
npm install
```

### Compiles and hot-reloads for development

```shell
npm run serve
```

### Compiles and minifies for production

```shell
npm run build
```

### Run your tests

```shell
npm run test
```

### Lints and fixes files

```shell
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
