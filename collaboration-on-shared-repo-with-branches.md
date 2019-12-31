# Collaboration with Branches

Before starting form groups of 3-4.  Pick one person to be the repository owner, they'll be called the __RO__ for the rest of these instructions.  Everyone else is collaborating on their repository, they'll be called __the team__.

> This set of exercises gently introduces the [fork -> branch -> merge -> PR] workflow.  You will be completing these exercises entirely from GitHub, no need for cloning!

---

__Part 0: The RO Creates a Repo__
1. The RO creates a new repository (with a README!)
1. Share a link to this repo with The Team

> _do not add The Team as collaborators to your repo!_
> If you do they can merge their own pull requests and this exercise won't be so helpful

---

__Part 1: Team Members Add a File__
1. Each member of The Team:
    1. Forks this new repository
    1. [Creates a new branch](https://help.github.com/en/articles/creating-and-deleting-branches-within-your-repository) called ```create-new-file```
    1. Adds a file named ```new-file.md``` directly from GitHub
    1. Commits their new file (_with a helpful commit message!_)
    1. (_pause_: what do you notice when you switch between branches?)
    1. [Merges ```create-new-file``` with ```master```](https://developers.sap.com/tutorials/webide-github-merge-pull-request.html)
    1. [Sends a Pull Request](./Pull-Requesting)  to the RO's main repository (from ```master``` to ```master```)
1. The RO then [reviews and merges](./Pull-Requesting) each pull request
1. Each member of the Team:
    1. Pulls changes from the main repository to their fork (from ```master``` to ```master```)


> __Check It! (before moving on)__
> - Does the RO's main repo contain a new file from each member of The Team?
> - Does each Team Member's fork have all the same files as the main repo?

---

__Part 2: The Team Edits one File__
1. The RO adds a new markdown file called ```favorite-colors.md```
1. Each member of The team does these things at the same time:
    1. (BEWARE - each Team Member _must_ pull __before__ the RO accepts any changes)
    1. Pulls changes from the main repo
    1. [Creates a new branch](https://help.github.com/en/articles/creating-and-deleting-branches-within-your-repository) called ```edit-file```
    1. Adds a line with their favorite color
    1. Commits their new file (_with a helpful commit message!_)
    1. (_pause_: what do you notice when you switch between branches?)
    1. [Merges ```edit-file``` with ```master```](https://developers.sap.com/tutorials/webide-github-merge-pull-request.html)
    1. [Sends a Pull Request](./Pull-Requesting)  to the RO's main repository (from ```master``` to ```master```)
1. The RO then [reviews and merges](./Pull-Requesting) each pull request
1. Each member of the Team:
    1. Pulls changes from the main repository to their fork (from ```master``` to ```master```)


> __Check It!__
> - Does the RO's main repo contain a new file from each member of The Team?
> - Does each Team Member's fork have all the same files as the main repo?

---
---
### <a href="https://hackyourfuture.be" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/63941625-4c7c3d00-ca6c-11e9-9a76-8d5e3632fe70.jpg" width="100" height="100" alt="Hack Your Future: Belgium"></a>
