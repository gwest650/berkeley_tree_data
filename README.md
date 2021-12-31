# Berkeley Tree Data


## Information about the data

[Download the data here.](https://data.cityofberkeley.info/Natural-Resources/City-Trees/9t35-jmin)

From the City of Berkeley:

> A GIS inventory of trees that are in the public right-of-way. 
> The dataset contains trees, planting sites and stumps. The inventory 
> was completed on April 30, 2013.

## Questions I would like the data to answer

* How evenly spread out are the trees in Berkeley or are they denser in certain communities?
* ~Are trees more common on private property as opposed to public property?~ I can't answer this question because the dataset only includes public trees
* What are the most common trees in Berkeley? Where are they most likely situated?
* ~How old are these trees?~  I can't answer this question because the data does not specify the age of each tree
* ~Are some more prone to be cut down?~ I also cannot answer this question, it would require further analysis in the notes column to specify if a tree is dying or has been cut down. 
* ~Is there a way to forecast what the tree landscape will look like in future years?~ I can't answer this question because we would need more information from the City of Berkeley


## Instructions for how to activate pyenv / Jupyter Lab

```sh
% cd coding
% cd berkeley_tree_data
% pyenv activate berkeley_tree_data-3.8.5 
% jupyter lab
```

## How to update my repo
```sh
% git status 
# look for modified and unstaged items
% git add README.md 
# use git add to add any other files that need to be added
# use git add . to add all the files
% git commit -m "updated README"  # this is called a "commit message"
# replaced what was inside the quotation marks is what I changed
% git push origin main 

```