# Intersection-of-Array
Here, yet an another amazing logic. what we need to do is, two given arrays , we need to print intersection of both, 
The intersection elements printed would be in the order they appear in the first array/list(ARR1)

Now what people generally do is.
They simply use 2 for loops, compare each element of ary1 with ary 2 , if matched , they print it.
But issue arises when case is like
11 11 15 16
11 21 31 15 19 10

here see, lets do a dry run
11 of ary 1 gets compared with 11 of ary 2 and gets printed
now again when 2nd 11 of ary1 gets compared to 11 of ary2, it again gets printed.
This is wrong as 11 should be printed only once.
So what we need to do
IF AN ELEMENT IS MATCHED, EDIT THAT ELEMENT IN SECOND ARY TO int_min, SO IT COULD BE NEVER COMPARED AGAIN.
