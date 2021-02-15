# About

This repo contains the set of tasks that would be essential to get hands on the workflow of git and github.

There are 4 default branches in this repo.
### develop:
Develop is the active branch for all incoming changes or new additions to the repository.

### staging: 
staging is the branch which contains proposed or accepeted contnt that may go to production in future.

### rollout: 
rollout contains content that is ready to go for main(production) branch in coming time.

### main:
Main is the production brnach that is the source of truth alll the time and is production ready anytime.

# Task

Following are the tasks along with the reference items on the topics. Please take the tasks in chronological order.

## Day 1
- Clone this repository.
- Create a new branch of any name.
- Create a new text file and add any content to it.
- Push the file to the repository.
- Create a PR to merge your work to develop and assign me to merge PR.
- Check if all the branches are consistent. If not, make them.

## Day 2
- Once all the branches share the same content, add another file with some content to branch develop and raise a PR.
- Get the PR merged to develop.
- Raise a PR to merge Develop to Staging, resolve any conflicts and get this merged.
- After the above is merged raise a PR to down merge staging to develop.
