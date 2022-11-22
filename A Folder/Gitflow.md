Gitflow
## What is it?
- Is an abstact Idea of a Git workflow
- Dictates kinds of branches and how to merge them together
- on OSX you can do brew install git-flow
## Develop and Main Branches
- Two branches that record the history of a project
- Main stores release history and has an abridged version history.
- Develop is an integration branch for features and has a complete version history.

## Feature Branches
- Each feature should reside in its own branch
- It branches from develop and gets back into develop
- **They never interact with main

## Release Branches
- Once develop has aquired enough features for a release you create a release branch from develop
- This starts the next release cycle so no features can be added after this point, only **bugfixes**, **documentation generation** and other **release oriented operations**
- When it's ready to ship, it gets merched into main and tagged with a version number and also merched into develop.
- Is important to merge back into develop because updates could have been made in the release branch
- This would be the ideal place for a pull request.

## Hotfix branches
- Used to quickly patch production releases
- They are a lot like feature and release branches except they branch out of main.
- As soon as the fix is complete it should be merged both into main and develop.

#git
#github
#gitflow
#projects
#jira
#atlassian
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

