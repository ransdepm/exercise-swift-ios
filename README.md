# Fueled Swift Exercise

> This repository is archived to prevent accidentally creating a PR against it.

A blogging platform stores the following information that is available through separate API endpoints:
+ user accounts
+ blog posts for each user
+ comments for each blog post

### Objective
The organization needs to identify the 3 most engaging bloggers on the platform. Using only Swift and the Foundation library, output the top 3 users with the highest average number of comments per post in the following format:

&nbsp;&nbsp;&nbsp; `[name]` - `[id]`, Score: `[average_comments]`

Instead of connecting to a remote API, we are providing this data in form of JSON files, which have been made accessible through a custom Resource enum with a `data` method that provides the contents of the file.

### What we're looking to evaluate
1. How you choose to model your data
2. How you transform the provided JSON data to your data model
3. How you use your models to calculate this average value
4. How you use this data point to sort the users

### Instructions
1. Clone this repo to a repo on your own Github account and **make it private**
2. Invite user `ransdepm` to collaborate on that repo
3. Address each step of the problem above and commit as necessary
4. Once you are finished, open a PR on your work (in your own repository) and assign `ransdepm` as the reviewer and notify your Six Flags contact via email.

### Duration
Out of respect for your time, we ask that you limit the amount you spend on this assignment to just a few hours. However, out of respect for us, we also expect you to submit the completed exercise within a week of it being assigned to you. Thank you, and best of luck!
