# Berkeley Tree Data


## Information about the data

[Download the data here.](https://data.cityofberkeley.info/Natural-Resources/City-Trees/9t35-jmin)

From the City of Berkeley:

> A GIS inventory of trees that are in the public right-of-way. 
> The dataset contains trees, planting sites and stumps. The inventory 
> was completed on April 30, 2013.


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