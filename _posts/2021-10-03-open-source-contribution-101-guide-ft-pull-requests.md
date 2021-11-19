---
layout: post
title: Open Source Contribution 101 Guide ft Pull Requests
date: 2021-10-03 07:40
---

First of all, before you guys tell me, Open Source is not about only Github and Pull Requests, this guide was written mainly to help beginners start out in Open Source and make their first pull requests. With that cleared, let's start the topic of the post.

If you want overall view of Open Source, check out here [Open Source Guide](https://opensource.guide/).

## What is Pull Request?

Suppose, you found out a open source project, where you want to work on some issue (a work that needs to be completed, feature to be added, bug to be fixed), or add features, make ammendments. So, you will get the repository, add your changes and make a request to the developer of the repository to add the changes to the original repository, and that request basically is called **Pull Request**.

But, how really?

## How do you Pull Request?

Before going into Pull Request, make sure you have these requirements:

1) Github account  
2) Git installed locally

If you have these things covered then lets get on to making a pull request. Pulling Request is very easy to do.

### Fork the repository

First of all, you fork the repository of your interest.

![Fork your repository](https://i.imgur.com/BuZn9fZ.png)

### Clone the forked repository

Then, you clone the forked repository. Remember, this is the copy of the original repository that exist as your repository. You must clone that by coping the url and performing `git clone` for that url.

![Cloning Forked Repository Step 1](https://i.imgur.com/KSEJCUK.png)

![Cloning Forked Repository Step 2](https://i.imgur.com/3pvPdCs.png)

### Read Guidelines

You should check the contributing guidelines, FAQs and check anything that might be mentioned for users to see before contributing to the project. Generally, everything will be mentioned briefly on the README.md, if not, it may also be on the root folder of the repository as respective file like `CONTRIBUTING.md`. 

### Make your changes

After checking the guidelines and following the guidelines, you can go add some changes, add features, fix bugs, work on issues, can be anything you can contribute.


### Push changes to your remote repository

After making changes, you need to push the changes to the repository.

1) Add any changed files for commit by `git add .` .  
2) Commit with a message describing shortly what you did by `git commit -m "<your-message-here>"`.  
3) Finally, push your changes by `git push origin main`.  

If you want to commit to another branch you can replace `main` with something else. To check the local branches do, `git branch` and to check remote branches do `git branch -r`. Old repositories generally has branch called `master` which was removed so as to remove any references to slavery by Github.

### Open Pull Request

After pushing the changes to your repository, check the repository on github. Note: This is the one that exists as a copy of your repository.

You might see something like `This branch is 1 commit ahead of repo:branch`. In place of `repo:branch` it can be anything that you are working on.

1) Click on `Contribute` and then `Open pull request`.  

![Open Pull Request Step 1](https://i.imgur.com/TJSR18x.png)

2) After that, Github compares and again asks if you want to create pull request. Click on `Create pull request`.  

![Open Pull Request Step 2](https://i.imgur.com/bA8lf4E.png)

3) Finally, you need to add Title and Description describing about your pull request. Description may contain template of how to write descriptions which is provided by the authors and maintainers which you should follow while writing descriptions.  

![Open Pull Request Step 3](https://i.imgur.com/79o7f1j.png)

4) After that `Create pull request` and you're done.  

So, after you're done creating a pull request, the authors and maintainers of repository will review your code and `merge` the pull request if everything abides to the project guidelines and you will get your changes added to the repository.

This wasn't that hard right? Now, you can go ahead and contribute to open source on your own.

Happy Coding!