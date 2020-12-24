# groupby

Pandas dataframe.groupby() function is used to split the data into groups based on some criteria. pandas objects can be split on any of their axes. 

Syntax: DataFrame.groupby(by=None, axis=0, level=None, as_index=True, sort=True, group_keys=True, squeeze=False)

.groupby() is split-apply-combine. Classified into 3 steps
* Split a table into groups 
* Apply some operations to each of those smaller tables
* Combine the results
