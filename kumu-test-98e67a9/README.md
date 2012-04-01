## Storage Strategies
The optimal strategy will be the one that diffs and merges best, and hopefully lends itself towards minification (all approaches will be able to be gzip'd to speed up downloads).

Use folders to separate the various data storage strategies and describe the strategy here:

## Lots of small files
Each table is its own directory, each record is its own file

## A couple large files
Each table is its own file

---

Each strategy should also consider various ways of storing the data (csv, json, haml).

##Gems & Bundler
Would groups be appropriate for indicating which workspace within an account a dataset should be used for? For example, an account has a file specifying which datasets it needs to include (and then those datasets may have their own includes) so it will run through and make sure to grab the appropriate datasets. 
