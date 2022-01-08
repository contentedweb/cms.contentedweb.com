---
date: 2022-01-08T06:59:06
tags:
- github
- forestry
- setup
title: Setting up a site

---
## Introduction

This post will take you through the steps required to setup a site using ContentedWeb.  It is assumed you are comfortable setting up accounts with services like online services, but you do not need any prior experience in using the tools.

There are two services you need to configure: [GitHub](https://github.com/) and [Forestry](https://forestry.io/), in that order. These instructions assume you are new to GitHub and Forestry. If you are an experienced GitHub or Forestry, user you probably don't need them.

## GitHub

### Step 1 - sign up

If you do not already have a GitHub account, you need to create one. Got to the [GitHub ](https://github.com/)site and click on Sign Up and then follow the instructions.

Once your account is created, login and keep a note of your username.

### Step 2 - copy the code

Next you need to copy the repository of the template site to you account. To do this go to the [eleventy-forestry-starter](https://github.com/contentedweb/eleventy-forestry-starter) repository. You will see a screen that looks like this:

![](/assets/images/eleventy-starter-1.png)

There are two ways to copy this repository into your account. You can either click on the "Fork" button towards the top right of the screen or you can click on the green "Use this template" button. In this guide we will do the latter. So click on that button. You will see a screen like this:

![](/assets/images/eleventy-starter-2.png)

For the repository name use the following: "**your-username**.github.io". So in the above example we would enter "contentedweb.github.io". You can give the repository a description if you want. Keep the repository public (since you will anyway be creating a public website from it) and ensure you **tick the "Include all branches" checkbox**.

The click on the green "Create repository from template" button to copy the repository to your GitHub account. After a few seconds you will see a screen like this which shows the code of your new repository.

### Step 3 - enable workflows

The repository includes some work flows which GitHub disables by default when copying a repository, for security reasons. You need to enable these as they build and publish your site when you are ready to publish changes. To do so click