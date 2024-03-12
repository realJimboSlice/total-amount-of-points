Total amount of points

Requisites:
Must write a function
Function must return total amount of points home team got


The games are in an array
The array contains strings
Each score is separated by a colon “:”
If home team wins award 3 points
If home team loses award 0 points
if home team draws award 1 point

How to do it:
We need to iterate through array - maybe with a for loop?
Have a variable called sum that contains the total amount of points - perhaps an int?
Every time the for loop loops through the array, the points should be added to the sum variable.

How does the function recognize the scores when it’s a string and how can we make the function separate the two numbers so that they can be compared?

Instead of separating maybe we should simply identify where the numbers are in the string and then simply use the string[] letter position method. 

Since the format is “1:1”, we could say string[0] and string[2]. That way we’ve got the two numbers that we need.
