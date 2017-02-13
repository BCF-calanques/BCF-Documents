Git and Github on the Calanques BCF
===============================================================================
*Author : Edlira Nano   
Licence : [Creative Commons Attribution Share-Alike 4.0 International
Licence](https://creativecommons.org/licenses/by-sa/4.0/?)*

The Calanques BCF (Bioinformatics Core Facility) is using both GitHub and/or SourceSup to host its projects.

## GitHub
On GitHub wre have an [organization page](https://github.com/TAGC-bioinformatics) where we put all our
  projects. 

### BCF organization 
In our GitHub organization, we create different 
projects containing
different repositories. A [GitHub
project](https://help.github.com/articles/about-projects/)
can contain a repository, issues,
pull requests, notes and makes collaboration very easy. GitHub users can become members and can
contribute to any project, and as admins they can also grant different
access levels to members :
see [the help here](https://help.github.com/articles/what-s-the-difference-between-user-and-organization-accounts/)
for more on this.  
If you want to become a member of an existing
project or to create a new one that you will administrate, send an email to
Edlira Nano : edlira.nano@inserm.fr or to Bianca Habermann,
bianca.habermann@univ-amu.fr.

### [Creating a repository project](https://help.github.com/articles/creating-a-project/)
  

Being part of a GitHub organization does not prevent a GitHub user
from continuing to have its own projects and repos into GitHub. In
these cases we recommend the use of the fork utility of GitHub (copy
option of git). Projects can be forked from one user account to a new
branch under the organization page, or the other way around. One can
then work on the repository that he wants and propagate the changes to
the other branches anytime. This can be done directly via git on command
line, or via the GitHub interface. There are also automatical ways of
synchronizing the forked repository with its upstream repository.

### GitHub's interface memo:
* To *fork a repository* : on the repository page on GitHub, click
button **fork** on the top right side (help [here](https://help.github.com/articles/fork-a-repo/)) 
* To *open a pull request* : on the upstream repo page, button **new
pull request** up front side, then **compare accross forks** to see
the changes for example. You can open pull requests from the upstream
to the forked branch or the other way around. So keep in mind that :
the base branch is where changes should be applied and the head branch
contains what changes you want to apply. This is explained 
[here](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)
* To *merge a pull request* : button **pull request** at the top
center then **merge pull requests** option.
* To *synchronise a forked repo with its upstream repo* so that
changes in the upstream repo are automatically pulled on the branch
see [here](https://help.github.com/articles/syncing-a-fork/).

However you decide to do things and to work with repos from your user
account into organization account, everything is possible graphically
from GitHub's website, but also via command line with git, the right
git options and the right repository addresses. 

[GitHub's help menu](https://help.github.com/categories/collaborating-with-issues-and-pull-requests/),
explains both graphically and command line possibilities, and contains
all help pages this document is pointing to.

## Git
### git command-line memo :
* to *see at what address your repository points to* :
`git remote get-url-origin`
* to *sync a fork* with the original repo :
[see helh here] (https://help.github.com/articles/syncing-a-fork/) and
[step 3 here] (https://help.github.com/articles/fork-a-repo/)
* to 8configure a remote* pointing to upstream repo
`git remote add upstream`
* to *verify all upstream and local repo* urls-s :
`git remote -v`

## SourceSup

You can access [SourceSup](https://sourcesup.cru.fr/) with the logins of your public research
intitute (INSERM, CNRS, University ...). People that are not part of
such an institute cannot login to SourceSup (but can have read and
write access to projects). 

On SourceSup every user that has access can create and manage a
project. SourceSup offers code versioning via git or subversion (you
choose), bug reports, issues, documentation, webpage for your project
etc. 

You can choose precisely who can read and/or write to your
repository on SourceSup : you can even allow that to users that have no access to
SourceSup (they are not part of a public research institute). [Here is
how to do that](https://services.renater.fr/sourcesup/gestion_utilisateurs).
