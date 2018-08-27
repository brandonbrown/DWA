# Milestone: Alpha Release

The Capstone Team will need some time to thoroughly review your Revised Project Spec and provide its approval.

You should begin working toward your Alpha Release, based upon your proposed Revised Project Spec, as early as you are able. The assumption here is that you will get notified if you are significantly off track and a more in-depth meeting would occur. Additionally, feedback and communication will likely be coming in continuously on the Pivot pull request.

## Milestone Pre-requisites

1. [x] Initial Pitch: Approved
2. [x] Initial Project Spec: Approved
3. [x] MVP: Approved
4. [x] Revised Project Spec: Approved

## Milestone Deliverables

1. [ ] Staging & Live Server Environments Established
2. [ ] Alpha Release of Codebase
3. [ ] Velocity Check

# Staging & Live Server Environments Established

With your documentation established, including the defined tech stack you will be using, for this milestone you will need to create the server environments for your Capstone Project to live within. This requires two environments: Staging and Live. The core idea here is that if you are working on a project for a client, you wouldn't want to disrupt the user experience on the live as you are testing new features on staging. So the live server will typically be one release behind what is currently being worked on. The Alpha Release is a touch different as there is not typically an earlier release to make.

That being the case, with the Alpha Release, you need to get your MVP working on the live server. This will require you to determine and test through getting all of the required server components installed, configured properly, and documented. Documented because you will need to recreate this EXACT environment in a second place, the Staging Server but with your next release of code rather than the MVP.

> For the Alpha Release: The Staging Server should contain all of the new features you are developing and polishing in tandem of building out these server environments while the Live Server should contain your MVP.

## Requirements

The listed pre-requisites for this milestone are required for evaluation. Failure to have completed the pre-requisites will result in a zero for this milestone. Please refer to the class's late policy regarding exceptions and late work.

* Server Environments Live & Staging
    * Configured to Support the Project Spec
    * Process to deploy has been documented in a step-by-step procedure
        * Procedure should be reusable on any specific commit or tagged release.
* Live Environment
    * Configured Identical to Staging Environment
    * Running the MVP's Codebase
* Staging Environment
    * Configured Identical to Live Environment
    * Deploy the Alpha Release Milestone's Codebase
* Codebase
    * Logical Design Patterns
* Environmental Variables
    * No Sensitive information in your repo (API Keys, Passwords, logins, or other credentials)
        * Also, No active info the history of a file. If you commit sensitive information, you must invalidate that information.
    * No hard-coded internal URLs or references. (Example: http://localhost, http://127.0.0.1)
* General
    * Follow the DWA Branching Model
    * Follow the DWA Style Guide
    * Issues are Up-to-Date 
        * If additional direction or approval regarding a issue occurs on a pull request, you need to link to that conversation as a comment to the original issue. This helps complexly threaded dialogs.
    * All feature direction is properly documented as issues, linked to the corresponding milestone's pull request, and has been executed accurately.
## Best Practices

* Logical and concise code comments
    * Comment only sections of code or particularly complex items. Do not comment every single line of code.
* [Semantic naming](https://24ways.org/2014/naming-things/) (files, functions, variables, id's, classes, etc...)
* Codebase is free from:
    * False Positives
    * Race / Async Conditions
    * Logical Errors
* Common Mistakes
    * [Multiple Projects In One Repo](https://youtu.be/H27HucyujUg)
    * [Folder Structure](https://youtu.be/CmTOW-29hpQ)
    * [Overly Complex Code](https://youtu.be/YlVhgyVfMUE)
    * [Bad .gitignore](https://youtu.be/iF9W8CeCfNM)
    * [Too Many Console Logs](https://youtu.be/TJO_NK4F1Ko)
    * [Attention to Detail](https://youtu.be/V_rHityy378)

## Documentation Standards

* Coherent and well structured `README.md` ([Example](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2))
    * Project Spec Docs should link off of the `README.md`.
* [Correct Instructions](https://youtu.be/G8pQR1ABGe8)
* [Well formatted / good informational hierarchy / skimmable content](https://youtu.be/cVwlMncCpFM)
* Should provide a clear and repeatable path for other developers to follow.
* All links / Images should not be broken.
    * Links to files within the repo should be relative so that the correct current branch is used when clicking a link in the documentation.
* Documentation should be in valid github-flavored Markdown.
* Should be well organized.
    * The main readme should contain quick access to all documentation. If a section of documentation requires significant explanation / takes up a lot of space, break it out into a separate .md file that the readme properly links to within a table of contents.


## Deployment Standards

Deployment of this milestone should be handled with the following criteria.

Prior to submission, ideally on the first day of the milestone's development, preform the following procedures:

* Determine the release version number using semantic versioning.
* Create a Branch called `[VersionNumber]` + `Release-Alpha` from your `Dev` Branch on github. 
* This should contain all merged and completed feature branches since your last release.
* Create a pull request for this `Release-Alpha` branch to merge with the base of `master`.
* On the Pull Request select to request approval from your primary Course Director 
    * Optional: Request approvals from any additional preferred members of your Capstone Project Team. Enter a new comment and tag those members requesting they review specific areas of your project.

On final Milestone Submission:

* Capstone members will need to view your project as a user. Add a comment and provide a links to the following.
    *  `Live URL` 
    *  `Staging URL` 
* If making a native mobile app, a video will need to be made. Keep in mind that through the development process multiple videos may been to be created to represent the current most state of your project.
* Add a comment to the `Release-Alpha` Pull request, requesting final approval.

Additional clarification may be needed by the Capstone team, please monitor this pull request until approval to merge is given. 

**Continue working on your project in the `Dev` branch using *feature branch development*.** Approval from your Capstone will take time to evaluate the submission in its entirety. This approval should not hold up development, however, and you should proceed with development. 

### APPROVAL

You have been approved to proceed forward! There may be additional considerations outline that should be addressed but you're doing well!

Follow-Up Actions: 

* Merge the Pull Request
* **Tag** the corresponding commit with the proper Semantic Version Number.
* Deploy the tagged commit to your 'live' server.
* Merge the `Release-Alpha` branch back into `Dev`, ensuring everything is up to date.
* Capture any additional feedback as new issues or add to any existing issues. These should be properly labeled, and assigned to an upcoming Milestone.

### REJECTION

You should suspend your current workflow and address the items outlined in the rejection notice that would be posted to the pull request and notify the Capstone Team once you have remedied the outlined items. Common reasons for rejection would be not following your project spec (once defined), not completing the pre-requisite elements of the milestone, or deviating significantly from the outlined requirements or requests made by the Capstone Team.

Follow-Up Actions:

* Notify Capstone Team once the pull request is addressing the issues outline and re-request review / approval.

# Velocity Check

At the end of the week your progress will be evaluated to see how many points you have earned based upon closed issues point value. Successfully completed issues will be tallied and a velocity will be established to help provide a baseline for the following week's work. You are able to use this velocity check to estimate if you are on track for completion of your issues from early milestones or if you are off track. This relies on accurate and honest usage of the issue system.

The Velocity Check will calculated by Zenhub and you can view it at any point. Your role in this requirement is to maintain your progress within the issue system of github and accurately estimate time per issue and as you close issues adjust that estimate to how much time was invested in each issue.

This is a pass/fail assignment where failing represents a significant drop in velocity, attributed to not using the issue system to correctly communicate, with the Capstone Team, your current and accurate progress or neglecting to make progress toward your set goals.

## Requirements

A specific velocity is not required, just the ability to calculate the project's velocity. The following requirements have been developed to ensure the velocity can be accurately checked.

* All milestones defined in your project spec have been created within Github.
* All issues are assigned to their specific milestone in Github.
* All issues have estimates.
* Issues are properly labeled.
* Milestone related issues are closed as they become complete.
    * Upon completion of an issue it is customary to update the estimate to reflect the actual time utilized. This should only be modified at the time of completion of the specific issue. 
    * Re-assigning time estimates to multiple closed issues at once is generally not accepted.
    * The Capstone Project Team may re-open issues that have erroneously closed or need further work. These re-opened issues will count against your velocity.
* Review your Velocity Report
    * With the Zenhub extension installed view https://github.com/USERNAME/REPO_NAME/milestones#reports?report=velocity