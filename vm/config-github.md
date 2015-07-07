---
title: Configuring your github account in the HMT VM
layout: page
---


Before you can commit and push to github, you need to configure your `git` settings in the HMT VM to tell it who you are on GitHub. That requires the following two commands. First,

    git config --global user.name "YOUR NAME"

YOUR NAME should be your real name (not your github user name).

Then,

    git config --global user.email "YOUR GITHUB EMAIL"

YOUR GITHUB EMAIL should be the email you used when you signed up for a GitHub account.

When you push, you will still be asked for your GitHub username and password.
