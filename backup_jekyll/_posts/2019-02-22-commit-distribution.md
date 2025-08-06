---
layout: post
published: true
title: Percentage commit distribution 
subtitle: Finding percentage distribution for your code commits
date: '2016-07-26'
tags:
  - code-quality
---

In highly complex projects there are multiple teams working on the same code base and there are bunch of tools to track the commit activities for each users.
The purpose of finding distribution is slightly different here – we want to see if we are doing more fixes rather than feature development 
e.g. if we somehow know the percentage distribution of **Bug Fixes/Defects Vs. Feature Development Vs. Other Changes** then we can focus more on code quality.

A simple change to enforce the **git commit message policy*** using `git server hooks` can give you good stats of your code base and the meaningful work we do within that.

e.g. If a team is doing 70% of its commits for fixing defects and 30% commits for feature development then definitely that is not a good sign of a code quality. Though this simple change cant give you immediate results you can definitely make it a practice and drill down to some meaningful conclusions which can results in high quality.
![Commit Distribution](/img/commit-dist.png)

The actual implementation details are [here](https://github.com/darshandeshmukh11/enforcegitpolicy) and refer my another [post on Linkedin](https://www.linkedin.com/pulse/predicting-bugs-your-code-darshan-deshmukh/) for further details.
