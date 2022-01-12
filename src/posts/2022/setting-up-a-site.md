---
date: 2022-01-08T06:59:06.000+00:00
tags:
- github
- forestry
- setup
title: Setting up a site

---
## Introduction

This post will take you through the steps required to setup a site using ContentedWeb.  It is assumed you are comfortable setting up accounts with online services, but you do not need any prior experience in using the tools.

There are two services you need to configure: [GitHub](https://github.com/) and [Forestry](https://forestry.io/), in that order. These instructions assume you are new to GitHub and Forestry. If you are an experienced GitHub or Forestry user, you probably don't need to follow them.

## GitHub

### Step 1 - sign up

If you do not already have a GitHub account, you need to create one. Go to the [GitHub ](https://github.com/)site, click on "Sign Up" and follow the instructions.

Once your account is created, login and keep a note of your username.

***

### Step 2 - copy the code

Next you need to copy the repository of the template site to you account. To do this go to the [eleventy-forestry-starter](https://github.com/contentedweb/eleventy-forestry-starter) repository. You will see a screen that looks like this:

![](/assets/images/eleventy-starter-1.png)

***

There are two ways to copy this repository into your account. You can either click on the "Fork" button towards the top right of the screen or you can click on the green "Use this template" button. In this guide we will do the latter. So click on that button. You will see a screen like this:

![](/assets/images/eleventy-starter-2.png)

For the repository name use the following: "**your-username**.github.io". So in the above example we would enter "contentedweb.github.io". You can give the repository a description if you want. Keep the repository public (since you will anyway be creating a public website from it) and ensure you **tick the "Include all branches" checkbox**.

Then click on the green "Create repository from template" button to copy the repository to your GitHub account. After a few seconds you will see a screen like this which shows the code of your new repository:

![](/assets/images/eleventy-starter-3.png)

### Step 3 - enable GitHub Pages

Next we need to turn on GitHub Pages. To do so click on "Settings" in the above screen and then click on "Pages" towards the bottom of the left-hand menu. You will see the following screen:

![](/assets/images/eleventy-starter-4.png)

Change the part where it says "Branch: **master**", to "Branch: **gh-pages**". To do so click on the button and choose "gh-pages" from the drop down:

![](/assets/images/eleventy-starter-5.png)

It should then look like this:

![](/assets/images/eleventy-starter-6.png)

If you wish to run your site under a custom domain, enter the domain name in the appropriate field above. You will have to configure your [domain name to point to GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

### Step 4 - build and publish your site

Now it is time to publish your site. To do this click on "Actions" in the menu and then on "Eleventy Build" under the Workflow heading on the left. Then click on "Run workflow" and finally the green "Run workflow" button.

![](/assets/images/eleventy-starter-7.png)

The workflow will now run and will take about a minute to complete. Once it has completed, your site should be live under the URL configured in step 3, eg "https://yourusername.github.io". If you don't see it, wait a couple more minutes. It can take a little longer until the HTML pages have been uploaded and published by GitHub pages.

## Forestry

Next you need to configure [Forestry](https://forestry.io/), so that you have a user friendly way of creating and editing content.

### Step 1 - sign up

Go to the [Forestry](https://forestry.io/) site and click on "Sign up" in the top right corner. In order to keep the process simple, just click on "GitHub" towards the bottom left of the page:

![](/assets/images/eleventy-starter-8.png)

This will use GitHub for authentication and logging into Forestry.  Run through the signup questions. It doesn't matter too much what you enter, but we would recommend "Other / Hobby / Eleventy" for the three questions it asks about your interests.

### Step 2 - add your site

Next click on the "Add site" button on the top right and then choose 11ty:

![](/assets/images/eleventy-starter-10.png)

and then GitHub:

![](/assets/images/eleventy-starter-11.png)

Next you have to choose the site from your GitHub repository that you wish to manage through Forestry. If you've been following these instructions you should see the repository you setup under GitHub step 2 on this screen:

![](/assets/images/eleventy-starter-12.png)

It should default to the master branch. If not, then choose the master branch as above. Click Next.

Forestry will import your site into it's system and ask you to complete the setup process. Since the setup for Forestry is already included in the starter kit, simple click on "Mark as done" on the remaining steps in the process:

![](/assets/images/eleventy-starter-13.png)

And then click on "Complete setup" to finish the setup process:

![](/assets/images/eleventy-starter-14.png)

Once setup is complete you will see a screen like this:

![](/assets/images/eleventy-starter-15.png)

### Step 3 - Personalising your site

Now you can start adding and editing content to your site. The first thing to do is change its title, subtitle and theme. To do this, click on "Data" in the left hand menu and then on "Contented CMS":

![](/assets/images/eleventy-starter-16.png)

This will open up a form for setting the site's title and other properties:

![](/assets/images/eleventy-starter-17.png)

When you are done, save the changes. You can also edit the pages and posts as well as creating news ones.

For more details on how to use the interface, you can read [Forestry's excellent documentation](https://forestry.io/docs/welcome/).

### Step 4 - publishing your changes

Because Contented CMS uses static pages, these need to re-built once you want to publish your changes. By default the site will be re-build every 24 hours at midnight GMT.

If you do not wish to wait that long, you can re-build the site manually. To do this you simply have to follow "Step 4 - build and publish your site" in the GitHub section above.

### Optional Step 5 - use your URL for Forestry

This step is optional.

If you do not wish to go to forestry.io to edit your changes, the CMS can also be configured to run under your own URL using "http://yourname.github.io/admin/" (or whichever domain name you configured for GitHub Pages. To do this go to Settings in the left hand menu, scroll down a little and click on "Deploy Admin":

![](/assets/images/eleventy-starter-18.png)

## Conclusion

You are now all good to go.

You copied the starter site into your GitHub repository, you setup GitHub Pages and then built and published your site. Next you created a Forestry account and imported the site into Forestry. Finally you made some content changes and published those changes. Your site is now live

If you have problems with any of the above or further questions on how to use the site, please contact me on Twitter: [@ContentedW](https://twitter.com/ContentedW).