---
date: 2023-09-18 07:46:57
layout: post
title: Initializing Git For Version Control
subtitle: Setting up Git for the first time for a new project
description: I'm recording the commands needed for setting up Git version control on a new project for future reference.
image: /assets/img/Git-logo.png
optimized_image:
category: version control
tags: git
author: Béhr
paginate: false
---
Embarking on a new project and setting up Git for the first time is a breeze! Just make sure you’re nestled in your project’s directory and get ready to type these five commands into your terminal.

Remember, this is a one-time setup per project. So, if you’re starting a fresh project, you’ll need to repeat these steps. But don’t worry, it’s just a one-time thing for each project.

> $ git config --global user.name "Your Name"
> $ git config --global user.email "you@youraddress.com"
> $ git config --global push.default matching
> $ git config --global alias.co checkout
> $ git init
