- Draft-

##Basic Workflow for Contributing/Developing a New Feature
1. Make sure to be on your master branch.
- To check which branch your currently on: ```git branch```

- To go to your master branch: ```git checkout master```

2. Update your local master branch to be in sync with the upstream master branch repository: ```git pull upstream master```
> NOTE: If there are confilicts, resolve them.
3. Review the changes and ensure they are satisfactory (run and test the project)
4. Push this to your remote origin repository: ```git push origin master```
5. Go to a branch to develop a new feature:
- To switch to an existing branch: ```git checkout existing_branch_name```

- To create a new branch and switch to that branch: ```git branch -b new_branch_name```

6. Sync your new branch with your master branch: ```git merge master```
7. Develop a new feature
8. Go back to your master branch (once you are sure that your current branch is good and ready to be put into master)
9. Merge the branch you worked on with your master branch: ```git merge your_branch_name```
10. Push this to your remote origin repository: ```git push origin master```



#Branching





1. Why use branches? 

by diverging from the main line of development, you can continue to do work without messing with that main line.

Useful Commands for Branching

- To create a new branch: ```git branch new_branch_name```

- To create a new branch and switch to that branch: ```git branch -b new_branch_name```
- To list 



#NOTE
- You need to commit your changes or stash them before you can switch branches; otherwise, your local changes will be overwritten.
- ```git pull upstream master``` is same as ```git fetch upstream``` + ```git merge upstream/master```