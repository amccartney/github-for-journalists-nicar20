# Github for Journalists
## NICAR 2020

Welcome to Github for Journalists!

## What is Github? What is git?

Beyond the fact that `git` is a mysterious piece of software I can barely fathom, it is a piece of software used for version control. Whenever you make changes to a file that is tracked by `git`, both the old and new versions of that file are preserved in case you need to refer or revert to an earlier version. 

Github is a website built on top of `git` that allows for easier access and sharing of repositories for people on teams or to the wider public.

## Why should I use it?

Github allows you to track changes you make to your files, which can be useful when you are writing code, but also for many other applications. Github is particularly useful when you have more than one person working on the same project at once, and need to keep track of who is doing what work and where. 

Github also natively supports display for several types of files like Markdown, which this page is written in. It can also display Jupyter notebooks, CSV files, images TK in the browser, making it easy to share work. 

## The ways you can use Github

### The browser
You can make changes to a Github project right in the browser if you want to. This is useful for making simple copy changes when you don't want to download the project to the computer. 

### The terminal
Most people who use Github for storing code projects interact with Github primarily through the command line, or terminal. This is the quickest way to manage your git projects, but also requires a working knowledge of git and other shell commands. 

If you are not familiar with these, do not be intimidated! We will not be focused on this during today's session, but it doesn't take too much time to get familiar with the flow of commands.

### The desktop app
The desktop app is the most user-friendly way to connect your local computer to your Github repositories. Most beginners start here. It provides a visual interface for uploading and downloading files to and from your remote repositore (on github.com), and tracking those changes. This is what we'll be working in today.

## Using the Github desktop app

TKTK put in slides/images etc. here TKTK

## Creating a new repository

1. Go to `github.com` and log in
2. Once logged in, a big plus sign should appear on the upper right corner of your screen next to your avatar. Click it, and choose `New Repository`
3. TKTKTK

## Basic commands

* `git clone`
* `git status`
* `git add`
* `git commit`
* `git push`
* `git pull`
* `.gitignore` files

## Create a personal Github page?

Github pages allow users to create a simple static site that's hosted right here on github.com. That way you don't have to deal with servers and such. You can also make a Github page for your projects, just like the one you are reading right now. They come with a variety of standard themes, or you can create your own.

If you are interested in creating a personal, organizational, or project page, check out this [handy guide](https://pages.github.com/).

## Scary Github warnings!!!

# 🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨
# Do not put passwords or other sensitive information in files you commit to Github!!! 

People will find them, and will make your life or your organization's existence miserable!

Remember too that Github preserves all versions of your code, so even past versions of your code can make you vulnerable.

Make sure to put any sensitive passwords or keys in a passwords file, and list it under gitignore so it won't be committed to your repository.
