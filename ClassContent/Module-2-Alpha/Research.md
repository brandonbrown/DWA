# Research

## Topics

1. [Deployment Workflow](#Deployment-Workflow)
2. [Continuous Integration](#Continuous-Integration)
3. [Live Environments](#Live-Environments)
4. Github Issue Client note action items
5. Velocity Check

---

# Deployment Workflow

Once a strong workflow is established we can build all sorts of automation into the deployment process so that small teams can operate efficiently and accurately when releasing.

Below are a few examples of using Github for workflow. Some of this might be review, but the examples are short enough that it is recommended you take a moment to refresh if that is the case. Otherwise, enjoy the concept of using Github as the central point for team communication and collaboration.

Once through some of the workflow we can start talking about automation and building elements into your servers to watch *the right branches* for changes on github.

If construct our live environment to watch for changes to the master branch of Github, and build the deployment processes we are able to smoothly and easily launch our new releases with minimal manual intervention.

Depending on your tech stack, automation may or may not be possible. For instance, if you are building an application that compiles to a mobile device, rather than a server based system that deploys to the cloud, there may be additional steps needed to take your releases live.

In either event, **your documentation should detail the release process**. This is so that if you take a six month break from your code and come back to freshen it up, or make additional releases, you don't need to spend hours picking though your notes trying to remember how exactly you were releasing.

Additionally, if you have multiple members on your team, expect other members to join, or need to show potential employers reviewing your code (more likely the case), that you can document the processes you build and would be a valuable asset to their team, these points of documentation are essential!

## [Exploration of a Collaborative Team Workflow](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) (4m video)

Here is a very tangible situation that illustrates how a strong workflow can coordinate all developers and other team members (like managers) can use github to collaborate on a codebase and bring it to a state of release.

## [Workflow Overview](https://www.youtube.com/watch?v=47E-jcuQz5c) (1m video)

A brief overview of the Github Workflow which is the foundation of how we will be conducting our releases.

## [DWA Branch Model & Workflow](https://www.youtube.com/watch?v=aJnFGMclhU8&feature=youtu.be)  (6m video)

A structured workflow is how you can become an efficient member of any team. As we look toward building our live environments our repo needs to be able to describe the state of our code in multiple places. Locally, on your developer's laptop the code will be in a different state than what you have last turned in / released. 

Similarly, users using a live service aren't utilizing the code that was created the last time the devs hit the save button, they are viewing the intentional state of the application the devs made when they last released.

A strong workflow will allow the smooth release of code from your dev environment into the live environment. This video covers how that process is done. We will ultimately need to create systems to react to the changes of our github repo, but the point here is that when we use the repo in a highly structured manner, there is no confusion of what code should be running on the live server and what code is still under development.

## [In-depth DWA Branch Model](https://nvie.com/posts/a-successful-git-branching-model/) (20m read)

Working with Git, Feature Branch Development has been great for your projects. But with deployment we are going to need our version control system to manage the states of our application as it relates to the code being developed. What is currently deployed, what has been deployed previously, what is ready to deploy next, and what code is being actively worked are the various states that github will be tracking for us.

This is a more in-depth exploration of the branch model that will be used.

## [Semantic Versioning](https://semver.org/) (3m read)

What is the difference between a version 1 of some software and a version 2? Devs and product owners have subjectively been making this distinction for a long time. Semantic Versioning is the attempt to take the subjectiveness out of versioning and apply meaning. It is all about backwards compatibility. 

Familiarize yourself with proper versioning as it is expected for when you are tagging your releases.

# Continuous Integration

## [Continuous Integration, Delivery, and Deployment Overview](https://www.digitalocean.com/community/tutorials/an-introduction-to-continuous-integration-delivery-and-deployment) (15m read)
A very good entry into the concepts of Continuous Integration, Delivery, and Development while providing some clear-cut contrast between each. This article outlines a lot of key terminology.

## [Continuous Delivery](https://devops.com/continuous-delivery-pipeline/) (5m read)
This read focuses more on Software Development than for releasing Web Applications but it does a good bit toward reinforcing the idea that iterating on a code base will yield enhancement overtime and with a Continuous Delivery Pipeline developers are able to release new features to end users quickly allowing for fast iteration cycles.

## [Simple Continuous Delivery Pipeline](https://www.madetech.com/blog/continuous-delivery-building-a-pipeline) (15m read)

There is no 'right way' to deploy, every system you will come in contact with will likely be a custom setup. For example, you will need to develop your own custom setup for your Capstone Project. This article explores a straightforward and simple approach for making our releases to a github codebase.

# Live Environments

If your tech stack requires you to build your own Virtual Private Server it is recommend using Digital Ocean with free credits from the [Github Backpack](https://education.github.com/pack). 

If you don't require the full power of configuring your own VPS I would recommend [Heroku](https://www.heroku.com/
) as another free solution. 

Careful with both, as when you start adding on many features you could be adding on additional costs. For this class, if anything but a free tier is required, discuss with your Course Director to determine any alternative options.

These resources are listed as optional as you should determine the ideal technologies for your specific tech stack. These videos are provided as a general getting started and are covered mainly for 

## [Optional] [Working within Linux](https://drive.google.com/file/d/0BxVGwcxbCTAtUDJPVUx4bVRoczg/view?usp=sharing) (20m guide)

Here is a cheat sheet guide that we will explore together in lecture. Browse through it and become familiar with the commands prior to the lecture.

## [Optional] [Setting up a VPS on Digital Ocean](https://www.youtube.com/watch?v=r2rIOj8-aJY) (5m video)

This is an older video I had created but the content is still good. The Digital Ocean interface has changed slightly, but using the content will get you where you need. Additionally, use a newer version of Ubuntu than the version I discuss in the video, instead, use **16.04 x64**.

> Reminder: Do not pay for this service, use the free credits offered in the [Github Backpack](https://education.github.com/pack) 

## [Optional] [Continuous Delivery with Heroku + Webhooks](https://www.youtube.com/watch?v=A1Z6TJ6CzaA) (1.5 hr video)

Previously recorded demo lecture. In this video I create a Heroku account, setup Continuous Delivery from my Github repo, experiment with Continuous Integration (Integrated Unit Tests) and explore Web Hooks from Github.

# Velocity Check

We will be using github issues in place of Trello. Trello is fine to get up and running with, but tracking features and the development process is best handled in one place, on github as issues. 

There is a tool that we will be using called [ZenHub](https://github.com/marketplace/zenhub), which effectively transforms github issues into a Trello board.

Please install the plugin to your browser, or if necessary, use chrome and install the extension and configure your issues. This will ideally reduce a significant amount of duplicate effort in communicating with the team on a separate platform.

To allow for the Velocity check please preform the following steps.

* Create all relevant milestones defined in your project spec.
    * Link would be:  https://github.com/USERNAME/REPO_NAME/milestones
* Ensure All issues attributed to the specific milestone are assigned
* Ensure all closed issues are in fact closed.
* Close the milestone
    * Link would be: https://github.com/USERNAME/REPO_NAME/milestones
* Review your report
* With the Zenhub extension installed view https://github.com/USERNAME/REPO_NAME/milestones#reports?report=velocity

Feature issues created should be in a User Story format and be properly labeled as feature.

Additional issues such as 'bugs' do not need to be in the User Story format, but should still be estimated and properly assigned to a milestone.