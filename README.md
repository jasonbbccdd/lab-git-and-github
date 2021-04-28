# Lab - Git & Github <!-- omit in toc -->
- [Additional Resources](#additional-resources)
- [Starter code](#starter-code)
- [Requirements](#requirements)
- [Setup](#setup)
- [Exercise 1](#exercise-1)
- [Excercise 2](#excercise-2)
- [Excercise 3](#excercise-3)

# Additional Resources
- [Git Guide Book](https://git-scm.com/book/en/v2)
- [Git Documentation of Commands](https://git-scm.com/docs)

# Starter code
- No starter code
- On the upper right, click `Fork` (Select your own account if prompted)
- Click `Code` and copy the `ssh link`
- In your terminal navigate to your course folder
- Use the command `$ git clone [ssh link] 121B-lab-js-array-problems`
- Run Code Runner

# Requirements
This lab requires 2 person and will be refered to `partnerA` & `partnerB`.

Once you have complete a set of excercise, switch roles and do it again.

# Setup
**PartnerA**
1. On the upper right, click `Fork` (Select your own account if prompted)
2. Add `PartnerB` as a collaborator

**Both PartnerA & PartnerB**
1. Navigate to the repo
2. Click `Code` and copy the `ssh link`
3. In your terminal navigate to your course folder
4. Use the command `$ git clone [ssh link] 122D-lab-js-git-and-github`

# Exercise 1
**PartnerB**
1. Create a branch called `feature/title`
2. Add `<h1>Lab Git</h1>`
3. Commit and push the `feature/title` branch
4. Create a PR for the `feature/title` branch
5. Assign **PartnerA** as a reviewer

**PartnerA**
1. Review PR
2. Request **PartnerB** to change `h1` to `Lab Git & Github`

**PartnerB**
1. Review comments
2. Make the change as requested
3. Commit and push the `feature/title` branch

**PartnerA**
1. Review PR
2. Mark as approved
3. Merge the PR

**Both PartnerA & PartnerB**
1. Pull changes from `origin/master` to `master`

# Excercise 2
**PartnerB**
1. Create a branch called `feature/authors`
2. Add `<h2>by [your-name] and [your-partner-name]</h2>`
3. Commit and push the `feature/authors` branch
4. Create and Merge the PR

**PartnerA**
1. Create a branch called `feature/location`
2. Add `<h2>Hong Kong</h2>`
3. Commit and push the `feature/location` branch
4. Create a PR and try merging (You shouldn't be able to as there are conflicts)
5. Resolve the conflict in Github
6. Commit the resolved conflict
7. Merge the PR

**Both PartnerA & PartnerB**
- Pull changes from `origin/master` to `master`

# Excercise 3
**PartnerB**
1. Create a branch called `feature/description`
2. Add `<div>this is an excercise for git and github</div>`
3. Commit and push the `feature/description` branch
4. Create and Merge the PR

**PartnerA**
1. Create a branch called `feature/hashtag`
2. Add `<div>#git #github #excercise</div>`
3. Commit and push the `feature/hashtag` branch
4. Create a PR and try merging (You shouldn't be able to as there are conflicts)
5. Pull changes from `origin/master` to `master`
6. Rebase `feature/hashtag` with `master`
7. Try pushing the `feature/hashtag` branch (You shouldn't be able to as you have change the structure)
8. Force push the `feature/hashtag` branch
9. Merge the PR

**Both PartnerA & PartnerB**
1. Pull changes from `origin/master` to `master`

