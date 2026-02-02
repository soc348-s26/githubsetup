# Git Branches 

Branches are a powerful feature of git. They make it possible to work on multiple tasks within your repository (or for multiple people to work) 
while isolating that work from other branches and your main branch.
Most of the time people try to keep the main (or master) branch for only work that is complete.  Therefore, you only "merge" your work into the main
branch when it is ready.

It's complicated to visualze and atthe same time have an accurate mental model of what git is doing.  This is 
probably especially true if you don't have some of the vocabulary (pointer, hash, graph) that people learn in 
computer science classes.  

Github actually uses a specific kind of branch for creating the pages that show on `github.io` called `gh-pages`.
If you look in your postcard repository and click on the branches button you will see that it has 3 branches.

*feedback* is the branch that I use to give you comments and potential changes.

*gh-pages* is the branch used to create your website using the steps described in the document on worflows.

Try changing to the gh-pages branch. 

Notice what the list of files looks like.  You should see `index.html` but not much else.   
For example there is no longer an index.Rmd file. And the .github directory is gone, along with all the files that we excluded in the workflow.

Switch back to your main branch.  

You can make a new branch in github by typing a name in the branch drop down. Make sure you are switched to the new branch.

In RStudio you can make a branch in the terminal window by typing

```
git branch <newname>
```
Putting in your new branch name.

In your new branch, change which postcard template is used.  You can also change other things, such as the image or other informatio. 
Commit the changes and go back to main.

Now make another new branch and use a third template. Commit those changes.

Switch between the branches and observe how the files differ.

In RStudio, you can try rendering your postcard while on each branch.  You should see the differences.

Next we will look at how to move your work from a work branch into the main branch.


