# Git Flow 
[![N|Solid](https://github.githubassets.com/images/modules/site/icons/footer/github-mark.svg)](https://docs.github.com/en/get-started) GET START WITH GIT
Git gives software developers the power to track, manage, and organize their code. In particular, Git helps developers collaborate on code with teammates, combining powerful features like commits and branches with specific principles and strategies helps teams organize code and reduce the time needed to manage to version. There are mainly 3 types of branch strategies have been flowed according to requirements. Git Flow is one of them. None of these workflows are set in stone and can, and should, be modified to fit your specific environment and needs.

## Flow Diagram 
[![N|Solid](https://www.gitkraken.com/wp-content/uploads/2021/03/git-flow-4.svg)](https://www.gitkraken.com/learn/git/git-flow)

## Git Flow Branch Strategy
There are five different branch types in total:
- Master
- Develop
- Feature
- Release
- Hotfix

The two primary branches in Git flow are master and develop. There are three types of supporting branches with different intended purposes: feature, release, and hotfix.

### Master Branch
The purpose of the master branch in the Git flow is to contain production-ready stable code that can be released in the marketplaces.
In Git flow, the master branch is created at the very beginning of a project and is maintained throughout the development process. The branch can be tagged at various commits in order to signify different versions or releases of the code, and other branches will be merged into the master branch after they have been sufficiently tested.

### Develop Branch
The develop branch is also created at the start of a project and is maintained throughout the development process, and contains pre-production code with newly developed features that are in the process of being tested.
Newly-created features should be based on the develop branch, and then merged back in when ready for testing.

### Git Flow: Supporting Branches
When developing Git flow, there are three types of supporting branches with different intended purposes: feature, release, and hotfix.

#### Feature Branch
The feature branch is the most common type of branch in the Git flow workflow. It is used when adding new features to your code.
When working on a new feature, you will start a feature branch off the develop branch, and then merge your changes back into the develop branch when the feature is completed and properly reviewed.

#### Release Branch
The release branch should be used when preparing new production releases. Typically, the work being performed on release branches concerns finishing touches and minor bugs specific to releasing new code, with code that should be addressed separately from the main develop branch.

#### Hotfix Branch
In Git flow, the hotfix branch is used to quickly address necessary changes in your main branch.
The base of the hotfix branch should be your main branch and should be merged back into both the main and develop branches. Merging the changes from your hotfix branch back into the develop branch is critical to ensure the fix persists the next time the main branch is released.

## Pros & Cons
### The Benefits of Git Flow:
	1	The various types of branches make it easy and intuitive to organize your work.
	2	The systematic development process allows for efficient testing.
	3	The use of release branches allows you to easily and continuously support multiple versions of production code.
### The Challenges of Git Flow:
	1	Depending on the complexity of the product, the Git flow model could overcomplicate and slow the development process and release cycle.
	2	Because of the long development cycle, Git flow is historically not able to support Continuous Delivery or Continuous Integration

- [Git flow] - Start with simple git flow step by step  
- [GitHub flow] - Understanding about github flow
- [GitLab flow] - Understanding about gitlab flow

[Git flow]: <http://datasift.github.io/gitflow/IntroducingGitFlow.html>
[GitLab flow]: <https://docs.gitlab.com/ee/topics/gitlab_flow.html>
[GitHub flow]: <https://docs.github.com/en/get-started/quickstart/github-flow>

