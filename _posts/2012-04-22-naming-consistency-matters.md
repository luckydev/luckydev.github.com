---
layout: post
title: Naming consistency matters
date: '2012-04-22T15:06:00+05:30'
tags:
- code
comments: true
---
When writing new methods, be it in Ruby or Objective C, I have always maintained a certain level of consistency in naming them. Many people underestimate this practice. So, I would like to point out a few advantages.
1. By just looking at the name of a method, i know what it does and what it returns. So it reduces a lot of jumps I need to make between files to cross check whether I’m using the right methods.
2. Class interface becomes very clean. What I mean is, new developers coming into the team need not read the entire implementation before using a method. This applies not just for new developers but for all of us (if we browse the code say 6 months after we wrote them).
3. Free documentation - if the methods are named appropriately, documentation is not all necessary for it.
This may look small, but over a period of time it will save you much more time than what you think.
