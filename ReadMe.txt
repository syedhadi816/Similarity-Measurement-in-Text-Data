There are 3 files in this folder
data50.csv
label.csv
group.csv. 

In data50.csv there is a sparse representation of the bags-of-words, with each row containing 3 fields: articleId, wordId, and count.
To find out which group an article belongs to, use the file label.csv, where for articleId i, line i in label.csv contains the groupId. 

Finally the group name is in group.csv, with line i containing the name of group i.