Create a repository
Initialized the repository
<< git init
Checked the status
<< git status
added and done the initial commit
<< git add.
<< git commit -m "Initial change"
Switched the master and created a new branch
<< git checkout -b updatestyling
Made the changes,added h2 and commited
git add .
<< git commit -m "added h2"  
Pushed the origin
Now switched the updatestyling to main again
Create another breanch named addedcontent
Make changes on the same line
Merge branch1 and master
And branch2 and master gets conflicts
![Screenshot 2025-05-06 135851](https://github.com/user-attachments/assets/ed753078-8b2f-4f62-9b31-500a23a0445f)













## ASSIGNMENT4 ##


## Git hooks are the scripts that git automatically happens or runs actions like checking code ,running tests etc before or after actions like:
git add

commiting code

pushing to repository

merging

checkout

## Git hooks located in .git/hooks/ folder inside every git repository

your project->.git/->hooks/->pre-commit.sample

                           ->post-commit.sample
                           
                           ->commit-msg
                           
                            ->pre-push
                            
                            ->post-merge
                            
## Managing hooks uses tools like

.Husky

.Lefthook

Hooks in automation

. Prevent mistakes early(like badcode,failing test)

. Save time

. Maintain quality

. Enforce rules

Husky provides the following

. Hooks are among

. Autosetup npm/yarn

. Cross platforms

. Scripts are tracked in repository

Husky mainly used in React, Angular, Node js projects.

