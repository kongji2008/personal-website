---
layout: post
title:  "Set Up My Local Dev Environment"
date:   2018-03-28
desc: "Set Up My Local Dev Environment"
keywords: "Dev Environment"
categories: [Java]
tags: []
icon: icon-html
---

### Step
- Install iTerm2 -> https://www.iterm2.com/downloads.html
- Install Prezto -> https://github.com/sorin-ionescu/prezto
	- make sure that you dont have a .zshrc, and if you do , to rename it for the time being.
	- prezto’s install script needs to write to a new .zshrc file so it can get loaded up when you start a new terminal
	- after you run the install script, just copy and paste your old .zshrc stuff into the new one.
- Install Sublime -> https://www.sublimetext.com/3
	- Some of packages should install
		- https://packagecontrol.io/packages/MarkdownLivePreview
		- https://github.com/saltstack/sublime-text
- Install Slack
- Install Java		
- Darcula Theme for IDE https://draculatheme.com/
- Install VistulBox
- Install Docker for mac
- Install Docker-machine (curl -L https://github.com/docker/machine/releases/download/v0.14.0/docker-machine-`uname -s`-`uname -m` >/usr/local/bin/docker-machine && \
  chmod +x /usr/local/bin/docker-machine)
- Install Homebrew
- brew install node
- brew install rbenv
- rbenv install 2.3.6
- rbenv rehash
- rbenv global 2.3.6
