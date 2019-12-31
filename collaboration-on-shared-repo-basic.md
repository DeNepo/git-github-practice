# Basic Collaboration on Shared Repo

Before starting form groups of 3-4.  Pick one person to be the repository owner, they'll be called the __RO__ for the rest of these instructions.  Everyone else is collaborating on their repository, they'll be called __the team__.

> This set of exercises have all work on ```master``` branch and cover only the most basic collaboration scenarios.

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
    1. Clones it to their computers
    1. Adds a file named ```<github-user-name>.md``` using VSC
    1. Commits their new file (_with a helpful commit message!_)
    1. Pushes their changes to _their_ fork
    1. [Sends a Pull Request](./Pull-Requesting)  to the RO's main repository
1. The RO then [reviews and merges](./Pull-Requesting) each pull request
1. Each member of the Team:
    1. Pulls changes from the main repository to their fork
    1. Pulls changes from their fork to their computers

> __Check It! (before moving on)__
> - Does the RO's main repo contain a new file from each member of The Team?
> - Does each Team Member's fork have all the same files as the main repo?
> - Does each Team Member's computer have all the same files as their fork?

---

__Part 2: The Team Edits one File (conflict time!)__
1. (you will most likely experience [merge conflicts](https://help.github.com/en/articles/about-merge-conflicts). this is ok! take the time to learn how this happens and what to do about it)
1. The RO adds a new markdown file called ```favorite-colors.md```
1. Each member of The team does these things at the same time:
    1. Pulls changes from the main repository to their fork
    1. Pulls changes from their fork to their computers
    1. Adds a line with their name and favorite color
    1. Commits their new changes locally
    1. Pushes their changes to their fork on GitHub
    1. Sends a Pull Request to the main repo with their changes
1. The RO then reviews and merges each pull request
    * The first PR should have no problems merging
    * After that you'll have lots of merge conflicts
    * Here's how to [solve simple conflicts from GitHub](https://help.github.com/en/articles/resolving-a-merge-conflict-on-github)
1. Each member of the Team:
    1. Pulls changes from the main repository to their fork
    1. Pulls changes from their fork to their computers


> __Check It!__
> - Does the RO's main repo contain a new file from each member of The Team?
> - Does each Team Member's fork have all the same files as the main repo?
> - Does each Team Member's computer have all the same files as their fork?

---
---
### <a href="https://hackyourfuture.be" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/63941625-4c7c3d00-ca6c-11e9-9a76-8d5e3632fe70.jpg" width="100" height="100" alt="Hack Your Future: Belgium"></a>
