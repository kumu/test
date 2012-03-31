## Storage Strategies
The optimal strategy will be the one that diffs and merges best, and hopefully lends itself towards minification (all approaches will be able to be gzip'd to speed up downloads).

Use folders to separate the various data storage strategies a describe the strategy here:

## Lots of small files
Each table is its own directory, each record is its own file

## A couple large files
Each table is its own file

---

Each strategy should also consider various ways of storing the data (csv, json, haml).
