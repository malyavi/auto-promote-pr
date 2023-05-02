# malyavi/auto-promote-pr
This action makes it easy to automatically promote a commit from a merged PR
to another branch.

To use this action, add it in your actions for your repository and modify the 
`promotionBranch` variable in the script to point to the promotion branch.
The default is `staging`.

You may also (optionally) modify the branches 
