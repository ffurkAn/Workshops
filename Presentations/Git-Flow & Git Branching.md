



What is Git-Flow ?
===================

The Git-Flow Workflow defines a strict branching model designed around the project release.

![<img src="https://www.atlassian.com/git/images/tutorials/collaborating/comparing-workflows/gitflow-workflow/05.svg">](https://www.atlassian.com/git/images/tutorials/collaborating/comparing-workflows/gitflow-workflow/05.svg)


-**master:** release history

-**develop:** integration branch for features

----------

###Others

-**feature:** new features, multiple features at the same time

Common conventions:
>- branch off: develop
>- merge into: master 
>- naming convention: feature-* or feature/*

**note:** never interact with master

----------
-**release:** next release

Common conventions:
>- branch off: develop
>- merge into: master and develop
>- naming convention: release-* or release/*

----------
-**hotfix:** maintenance

Common conventions:
>- branch off: master
>- merge into: master and develop
>- naming convention: hotfix-* or hotfix/*>

----------

## Using Git-Flow 
>- using commands
or
>- using SourceTree


---------

##Example
For a basic example about Git-Flow, click [here](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

Useful Links
------
>- [https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

>- [http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/](http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/)
