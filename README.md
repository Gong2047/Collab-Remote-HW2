## **Assignment 2 - Git Mission Statements**

### **Description**

Develop an effective Mission Statement using Git branches to iterate on and A/B test a series of candidates.



### **Implementation**

1. Set up a new Git and public GitHub repo for this assignment. Make sure your repo has a sensible README.
2. Create a new branch with an appropriate name from your initial commit in main. You will use this branch to test out new versions of the Mission Statement. Run the `git push origin <name>` command to track this branch on GitHub.
3. Choose an existing company’s Mission Statement, or invent your own for a real or fictional company, as a starting point.  **On each of your branches**, put this phrase into a new file called `missionstatement.txt`, and make sure it is committed and pushed to GitHub.
4. On your testing branch, rewrite the current Mission Statement in an attempt to make it the company’s vision more clear. Don’t be afraid to change any and all of existing text, really make an effort to really identify the weaknesses in the current statement. You may wish to share this Mission Statement with a classmate to get their feedback. Commit and push the new Mission Statement, replaced in `missionstatement.txt`, to GitHub.
5. Perform Step 4 at least 3 times to meaningfully transform the Mission Statement into something new.
6. Switch to the branch with the starting Mission Statement (run `git checkout main`) and merge in the changes from your testing branch (run `git merge <name>`). Use the resulting merge conflict to evaluate your two Mission Statements. Resolve the merge conflict in the manner of your choosing such that you end with whichever statement you like best. Commit the final Mission Statement and push it to your GitHub repo on the main branch.
7. Submit your GitHub URL for this assignment on Brightspace.



### Grading Rubric

| **Points** | **Criteria**                                                 |
| ---------- | ------------------------------------------------------------ |
| 2          | Make a repo with a Mission Statement                         |
| 4          | Iterate on Mission Statement in a separate branch            |
| 4          | Merge branches together to determine the better Mission  Statement |

 
