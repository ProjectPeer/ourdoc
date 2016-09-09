# GitHub

There will always been 2 branch on which we will never push our work :
- `master` which is the production branch,
- `dev` which is for the development.

We will work using branch. A branch must be created to contextualize the work that have to be done, fo example If I want to create some graphical elements, I will create a branch "design-update".

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Steps
- Create a branch based on the "dev" branch : `git checkout -b "branch name"`,
- Use this branch for local work,
- At any moment, you can push this branch : `git push "remote" "branch name"`,
- Next, make a pull request comparing the using branch with the "dev" branch, the code will reviewed or discusted,
- If the code is validated, it have to be merge if there are no conflicts. Otherwise the devloper that push the branch have to solve the conflicts.
- If you no longer need the branch, delete it.

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Commit convention
Prefix the commit messages using these words :
- FEAT: new features,
- CHANGE: code modifications,
- FIX: bug fix,
- REFACT: refactoring and code structuration.

In case of a commit contains a lot of goals, choose the more important word. Here is an example of commit message :
`CHANGE: site banner`

The commit messages should be writed in english. The message must talk about the modifications that the commit bring.

If a commit bring a ticket solution, add `closes #ticket-number1 #ticket-number2 ...` in the commit message. You can also do the same in a pull request.

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

# Tickets
If a bug is discovered, you have to write an alert using the GitHub tickets.

The tickets must contains these elements : 

```

WHERE : the bug location.

BUG REPRODUCTION : the action made to display the bug.

DESCRIPTION : bring precisions about the bug.

```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)
