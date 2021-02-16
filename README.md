# About

This repo contains the set of tasks that would be essential to get hands on the workflow of git and github.

## Setup ssh for github: 
- https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

For any git reference: 
- https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud
- https://try.github.io/
- https://www.tutorialspoint.com/git/index.htm

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
- Check if all the branches are consistent. If not, create a new branch off develop and share your approach to make them consistent in a file.
- Raise a PR to add your stategy to develop.

## Day 2
- Cut a tag RL-1 on develop and create a branch out of tag as release/RL-1.
- Raise a PR to merge tagged branch to Staging, resolve any conflicts and get this merged.
- After the above is merged raise a PR to down merge tag to develop.

## Day 3
- Cut a tag on staging and prepare this tag for rollout.
- Merge the tag to rollout.

## Day 4
- Make a `merge commit` on develop.
- Revert that commit.
- Raise PR to sync up all branches.
