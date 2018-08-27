# Research

## Topics

1. Linux Commands
2. Automation with Gulp
3. Deployment Patterns

---

# Linux Commands

## [SSH & SCP in Linux](https://linuxacademy.com/blog/linux/ssh-and-scp-howto-tips-tricks/) (20m read)
SSH is the backbone of connecting to remote computers and SCP is a tool to securely copy files across remote connections. This article goes into some of the finer points of how to move multiple files from, say, your local environment, to a remote server for a manual deployment. Sprinkle in some webhooks and you might be able to trigger these automatically in the future ;)

## [Bash Scripting in Linux](https://ryanstutorials.net/bash-scripting-tutorial/) (tutorial series)
A high level understanding of Bash Scripting is highly encouraged and if you intend on doing any automation this resource can be used as a cheat sheet on how to craft your bash scripts that will execute your deployment calls and webhooks!

# Automation with Gulp

## [Automating with Gulp](https://hackernoon.com/how-to-automate-all-the-things-with-gulp-b21a3fc96885) (14m read)
Gulp is a critical tool in writing tasks that will help to take the human component out of deployment. Common tasks like increasing the version number of your application, in all the various places (readme, package.json, etc...).

## [Automate your Deployments with Gulp… Start Here](https://withouttheloop.com/articles/2016-05-26-automating-deployment-of-nodejs-applications/) (15m read)
This article starts to open the can of worms for automating deployments. I wanted to put this in front of you so that you know of some of the key tools needed to launch and deploy a node application and a rough framework to start automating your application deployments even if you are not deploying a node project, as you can use node locally, as a dev tool.

## [Touching on Gulp and Grunt](https://www.lynda.com/Node-js-tutorials/Grunt-Gulp/573614/577277-4.html?org=fullsail.edu) (3m video)
You will see lots of uses cases for build automation tools on the front end, so spend some time getting familiar with that but also think toward how you could use these tools on the back-end to make your life easier and less prone to error.

# Deployment Patterns

## [Thoughts on Web Application Deployment](https://omniti.com/seeds/thoughts-on-web-application-deployment) (15m read)
This article has a great technology agnostic approach to discussing what should be considered for making releases to a project. It does a pretty good job of filling in the 'why are we doing things this way?' gaps in the class from a very high level. If you're feeling lost at all in the content, this article should ground you and help to tie everything together.

## [A/B Testing, Blue/Green, Canary Patterns](http://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/) (10m read)
There are a number of deployment patterns that have been developed that each try to tackle effectively delivering your application to your users. Sometimes though there are going to be bottlenecks that we need to get around or situations that need mitigated. A/B. Blue/Green, and Canary Deployments are some common solutions to these problems. This article outlines the mechanics of each concept.

## [5 Awkward Questions for the Production-end of the DevOps Pipeline](http://www.joetheitguy.com/2017/11/22/5-awkward-questions-production-end-devops-pipeline/) (5m read)
Too often do we, developers, look at a project as if it were brand new. By this we think solely about how best to build something. This article explores 5 concepts of updating something that exists, and the considerations that need to be attended to with the existing system and trying to not blow it up while releasing the new version.

## [Canary Deployments](https://martinfowler.com/bliki/CanaryRelease.html) (5m)
Here is a bit more info to aid you in your understanding of Canary releases.

## [Releasing at Scale - Deployment Plans and Patterns](https://youtu.be/4Va1JanO7O0) (1hr video)
This is a good sampling of a number of release focused developers / engineers in the industry discussing their experiences around each of the deployment patterns we are discussing in this course. This video does a good job at covering a bit of why the various patterns are needed, not just what they are.