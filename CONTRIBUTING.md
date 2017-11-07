# Contributing

Take a look at our issues page. If there is something you'd like to work on, leave a comment saying just that and a maintainer will assign you to the issue. If you need any help along the way or have any questions, leave a comment. Feel free to mention @ifiguer.

Next, assuming you have your developement environment set up (if not see instructions on our README), create a branch. By convention branch names are either `feature/<feature-name>` or `issue/<issue-name>`. So if you have an issue, say `docker warning`, create a branch `issue/docker-warning`. This is just to keep things organized. 

At this point start your development. There is probably no need to get updates from master and merge them into your branch along the way, so only do this if necessary. When you are done, commit your changes and push them to remote. 

Finally, go to `https://github.com/ISUWeb/it-clubs/pulls` and create a new pull request. It will ask for a title and a comment. Make the title meaningful and in the comment follow the convention of mentioning your issue number. So if you are working on issue number 42, your comment should look like: "See #42 - <insert-awesome-description-here>". You will at least one developer (can't be yourself) to review your changes and approve them.

Once your pull request is approved, delete your branch locally via `git branch -d <branch-name>` and on GitHub. 

One last thing you may want to do is leave a comment on your issue explaining how you solved the problem, which may help for future reference.