## Useful_R_terms
This is a place to note useful R terminology. <br/>
1. setwd() -> set working directory. <br/>
2. getwd() -> get working directory. <br/>
3. head() -> displays the first few rows of your imported data set. <br/>
4. tail() -> displays the last few rows of your imported data set. <br/>
5. str() -> informs you whether the variables in your imported data set are continuous, integers, categorical or characters. <br/>
6. class() -> tells you what type of variable you're dealing with. <br/>
7. '==' -> tells R that the term must be exactly as you stipulated. <br/>
8. csv. -> comma seperated values and is the best form of data to use in R. 
9. function(x,y) -> allows you to create a function in R. The function arguments don't necessarily have to be x and y, they can be any letters or phrases. <br/>
10. for() -> allows us to create a loop that iterates through a number of items normally stored as a list. This function will be performed on each item equally on the list. <br/>
11. list() -> creates an empty list unless there is something in the brackets. <br/>
12. lapply() -> this is another loop function, where the first argument gives the list objecy to be iterated over whereas the second argument defines an unamed function. The apply loop is easier and faster to use than the for() loop. <br/>
13. sapply -> gives more readable outcomes from the lappy() loop. <br/>
14. ifelse() -> this is a conditional statement that tests for some logival TRUE/FALSE condition in the data. It can thern perform one of two actions depending on the outcome of the test. <br/>
15. <,<= -> is smaller than, is smaller than or equal to. <br/>
16. >,>= -> is larger than, is larger than or equal to. <br/>
17. != -> not equal to. <br/>
18. %in% -> belongs to one of the following, usually followed by a vector of possible values. <br/>
19. & -> is the AND operator and allows you to chain two conditions which must both be met. <br/>
20. ! -> not operator, to specify things that should be omitted. <br/>
21. gather()-> converts wideformat tables into a tidy dataframe.
22. spread() -> does the inverse of the gather() function.
23. select()
24. filter()
25. mutate()
26. summarise()
27. case_when() -> conditional functions.
28. tally() -> 
29. group_by()
30. ungroup()
31. grepl() -> looks for patterns in a group of data.
32. seperate() -> part of the tidyr package. Allows for a single column to be split into multiple if there is a space between words (i.e. Latin Names).
33. aes() -> tells the plot to colour the dots according to a specified factor.
34. do() -> is a function that allows us to do pretty much any R function within a pipe (%>%).
35. paste() -> allows you to combine text string outputs from functions or object names in the environment.
36. bind_rows() -> is a function that allows us to stick together sets of data into one dataframe provided they already have the same format.
37. > Set operations use x and y as two sets of data.
> * setequal(x,y) -> returns TRUE if x and y are identical.
> * intersect(x,y) -> finds observations present in both x and y.
> * setdiff(x,y) -> finds observations present in x but not y
> * union(x,y) -> finds unique observations in x and y
> * union_all() -> retains duplicates
38. arrange() -> puts the data in order according to whatever is in the brackets.
39. bind_cols() ->
40. parse_number() -> removes a specified symbol/ value from a group of observations (i.e. can remove the 'X' from X2000, X2001, X2002,...).
41. > Mutating joins use x and y as two sets of data.
> * inner_join(x,y) -> keeps observations appearing in both datasets.
> * left_join(x,y) -> all observtaions in x and only adds matches from y.
> * right_join(x,y) -> opposite of left_join and can also be achieved by using left_join(y,x).
> * full_join(x,y) -> keeps all observations in x and y; if there is no match between data sets, it will return NAs.
>
