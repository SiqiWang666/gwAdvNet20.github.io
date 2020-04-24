---
layout: page
title:  "Assignment 4: Technical Blogging 2"
permalink: /assignments/technical-blog-2/
---

> For the final assignment you can choose between writing a [technical blog](/assignments/technical-blog-2/) or implementing the [leader election portion](/assignments/raft-election/) of Raft.

In this assignment, you will write a second blog post on a distributed systems topic that interests you. This will be similar to the first networking tech blog you did, but there are a few special requirements.

## Topic Selection

Your blog should be focused on describing a small project that you build. You can pick from two options:

  1. Build something using a fault tolerance library such as [etcd](https://github.com/etcd-io/etcd), [zookeeper](https://zookeeper.apache.org/), [consul](https://www.consul.io/), etc. For example, you could create a simple web interface to an `etcd` based key value store.  Your blog post would describe the library you used and the APIs needed to construct your service. Note that you do not need to create a very complicated application, instead think of it as your blog is providing a basic tutorial for using the library you have chosen.
  2. Build something by combining several AWS cloud services. For example, you could deploy a web server and test the performance of the different types of load balancers that AWS offers. Again, we are less focused on you building something creative, and more interested in seeing you provide a good writeup on how to use the services you have selected. *For a group with `g` members, your project needs to include `2*g` different AWS services.* (The max group size for this assignment is 2)

*Note:* Your AWS Educate accounts are somewhat limited in what cloud resources you have access to.  If there is a service you want to use that is not available in your account, contact Prof. Wood and he may be able to get you access in another account.

> *You **must** get your tech blog plan approved by us in advance. Post a one sentence description of your plan in #a4blog on Slack and tag both of us.*

## Blog Writeup

Your writeup should follow the [basic guidelines from the prior assignment](/assignments/technical-blog/).

As before, you should create a fork of the class website repository (you may already have this from the prior assignment). Put your post in `wiki/somename` where `somename` is a short description of your topic.

**Base Requirements:** 
 - Must be long enough to be interesting (at least 750 words)
 - You must write some code or run experiments
 - Present useful information in an understandable way 
 - Present useful information in a visually appealing way.
 - Work by yourself or with one other person.
 - *All* members of the group must contribute (i.e., commits cannot all be made by a single user)

**New Requirements:**
 -  *Any images in your blog must either be your own or you must cite where they are from.* Don't steal simple diagrams from other websites -- make your own!  In general, the only time you should be using an image from another sources is if it is something that you could not create yourself (e.g., a picture of the inside of Google's data center).
 - Use footnotes for citations to sources of information where relevant. See [how to make footnotes](https://stackoverflow.com/questions/25579868/how-to-add-footnotes-to-github-flavoured-markdown).


## Submission
To submit your blog, you should create a pull request named with the title of your post. The PR description should include:

  - Your team name and members
  - Which team members contributed which parts

Then tag us in the PR body using our github usernames(`@twood02` and `@thelimeburner`).

