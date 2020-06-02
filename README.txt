GIT MERGE
Introduction
Merging is a process of combining various git branches together as one. Git can automatically merge the changes on different branches together. This branching and merging ability is what makes Git incredibly powerful! You can make small or extensive changes on branches, and then just use Git to combine those changes together.
 Git Merge Command
Command -----> git merge 
Git Merge Process 
 When a merge happens, Git will:
•	look at the branches that it's going to merge
•	look back along the branch's history to find a single commit that both branches have in their commit history
•	combine the lines of code that were changed on the separate branches together
•	makes a commit to record the merge
 Git Merge Types
There are two types of merges:
•	Fast-forward merge – the branch being merged in must be ahead of the checked out branch. The checked-out branch's pointer will just be moved forward to point to the same commit as the other branch.
•	the regular type of merge
o	two divergent branches are combined
o	a merge commit is created
 
Steps to Git Merge
1.	Fork / Clone Git Repository 
2.	Branch and Checkout from the master repository 
3.	Create Pull Request in order to review code changes made to the project [optional]
4.	Git merge the branched repository to the master.
