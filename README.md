# Git

###### To make learning process more fun, all the practice tasks will be performed on a website, which contains some memes about Git. Every time you change the code, you can open the website and check out new memes there. You can start from opening _index.html_ in your browser. Enjoy :)

##### To complete this topic, you need to make all the following steps done:

1. Install Git (if you still didn't do that);
2. Configure git with your name and email;
3. **Fork** this repository (all the next steps must be done **in your forked repository**);
4. Clone the repository to your local machine;
5. Create and checkout to branch `feature`;
6. Change `merge.png` to `in_case_of_fire.jpg` in _merge.html_ and commit the changes.
Don't forget to use commands like `git status` to check the status of your repository, and write [good commit messages](https://chris.beams.io/posts/git-commit) ;)
7. Checkout to `master`, then create and checkout to branch `killer-feature`;  
8. Change `merge.png` to `conflicts.png` in _merge.html_ and commit the changes;
9. Checkout to `master` and merge `feature` into it and right after that merge `killer-feature` to `master` (don't forget to check, what's going on with the website in the browser);
10. Resolve the merge conflict))) Let changes from `killer-feature` be in master;
11. Checkout to `feature` and rebase `master` on it;
12. Delete `killer-feature` branch;
13. Change `revert.jpg` to `revert_revert.jpg` in _revert.html_ and commit the changes;
14. Revert the latest commit;
15. Checkout to `master`, change `reset.png` to `one_does_not_simply.jpg` in _reset.html_ and commit the changes;
16. Checkout to `feature` and cherry-pick the commit from previous step;
17. Checkout to `master` and hard reset it to `origin/master`. Then push the changes to the remote - if everything was done right, it should return _Everything up-to-date_;
18. Checkout to `feature`, change `real_version_control.png` to `merge_me_in.jpg` in _index.html_, commit the changes and push them to `origin/feature`;
19. Create a merge request from `feature` to `master` **of your forked repo** (invite, if necessary, and assign your topic teachers) and wait until the merge request is approved;
20. After getting the approve merge the request to the `master` (**squash the commits** and **do not delete the source branch**) .

## Well done!