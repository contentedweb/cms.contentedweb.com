---
title: About Contented CMS
menuLocation: top
eleventyNavigation:
  key: About
  order: 200

---
## Starter kit

This is a basic starter kit for [Eleventy](https://www.11ty.dev/), with [Forestry](https://forestry.io/) for editing and [GitHub Pages](https://pages.github.com/) for hosting baked in.

This kit is largely based off the [Eleventy starter site](https://github.com/11ty/eleventy-base-blog) and has been adapted and styled to be a simple blogging website. The aim is to make it as easy as possible for non-technical users to set up a blog using a static site generator, in much the same way the might get started using [Wordpress](https://wordpress.com/). Of course it can in no way compete with Wordpress on functionality, not even a little. That was not the aim.  Instead the focus is on speed and simplicity. 

The idea for this kit comes from my experience of moving from a Wordpress hosted site to a site built by Eleventy: "a simpler static site generator". Eleventy is indeed a great tool, but you do need quite a bit of technical knowhow to get a site configured, hosted and editable through a user friendly interface.

## Why static pages?

Few websites are updated so frequently that they need to be generated on the fly every time someone them. Equally, few websites are so large that rebuilding the entire site as static pages on each update would be considered wasteful. But the real benefit is the speed. Nothing can beat the speed with which a browser can load and display simple static pages.

## Static means static

In the case of the [starter template](https://templ.contentedweb.com/) this includes no client-side JavaScript. This was a design philosophy of mine. There is little need for JavaScript on simple websites. For sure JavaScript has it's uses but it also increases complexity. So for this starter site, there is no client-side JavaScript. This means no config settings for things like Google Analytics or Facebook. This is as much about ethics as statics. Is the ethics of Google or Facebook tracking every single one of your users worth you knowing how many hits your site had? Server side stats can easily accommodate that and do not require the tracking of your users across the users.

Of course since this is only a template site, it is not hard to add the required code for services like Google Analytics. You won't find the how-to for that here though! Just be cool instead😎  

## The tools

After trying out various online services to manage my blog I settled on Forestry and GitHub Pages. There are many other services available, but the combination of these two was the simplest for me. I had two aims when choosing services: keep it simple and keep it simple.

### Page generation

I chose Eleventy for my server side static page generation purely because I liked the sound the of it. I didn't want to get involved in any tool where the focus was on client-side rendering or single-page-apps. I wanted a traditional site where is each URL maps to a static file on the server. I also wanted the tool to use a JavaScript, which is a programming language I am somewhat familiar with. What I found was that many tools based no JavaScript seemed go down the client-side rendering route, at least out of the box. Quite possibly this is incorrect, but it doesn't matter. I liked the philosophy behind Eleventy and so got started with that and never looked back. 

### Editing

For editing I chose Forestry because for a simple site, being managed by one person, it offered the best experience. There are [many other editing tools available](https://jamstack.org/headless-cms/), but for me Forestry did exactly what I needed and no more. 

### Hosting

For hosting, since the site's code is anyway hosted on GitHub and GitHub offers a basic hosting service, it made sense to use GitHub pages to host the site.

## Themes

The kit includes some basic the themes so you can easily change the look and feel of the site. Of course since it is all open source and hosted in GitHub you can make more complex styling changes directly in the CSS code and Eleventy templates.