### Way of working

The way we plan and do work together will probably always be changing and if it starts to differ from what this text
is saying that is probably a good thing - it means we are evolving. Just remember to update it before the next person goes through the
onboarding process (It's always OK to do a pull request).

## Retro/Demo/Planning

### Retro
Once a week the team has a meeting with the product group (Ida, Niklas, Marcus J) where we mention what we have been
doing the last week and also talk about what went well, bad, how we feel, what we can do better and such things.
This is a good forum to bring up changes you want to how we work.

### Demo
Sometimes we demo new things for eachother and the product group to show what we have been doing and also to get feedback.
There is no rule to always demo something and you shouldn't go way off with hasted code hacks for the sake of a demo.
That can lead to bad code quality and consume a lot of time fixing them after.

### Planning
We plan what we should focus on until the next weekly meeting. We don't do detailed time estimates for work but we might
set some goal.

## Github
All of our code base and a lot of other documentation are stored at github.
### Issues
We continuously create new issues on github where we describe bugs/new requirements/upgrades/any work needed, and we use them as a backlog.
New issues should also exist on one of [our project boards](https://github.com/orgs/insurello/projects)
in github if it fits there. Issues can be assigned to the people working with it.

### Branches
When you are ready to start coding on a solution for an issue you always start with creating a branch on the repository
you plan to work on. Name the branch with something that matches the name of the issue. When you are done or if you just want
a code review you create a Pull Request (PR). If don't feel completely done yet but still feel like a code review would be
nice put "WIP" in the branch name (work in progress). Put some effort in writing a good description of what problem the PR
is trying to solve and what changes the solution brought. When code review is ok you can "Squash and merge" the code
into master. The approval from a reviewer is mandatory and you cannot merge to master without it.

### Code reviews

### Release
Our repositories are setup to release new code when a branch is merged to master and we strive to be able to do it as
often as possible.
