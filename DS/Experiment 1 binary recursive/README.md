# AIM OF THE EXPERIMENT:  To write a binary search program using recursive function.
BINARY SEARCH : to find a key element in an given array in which the elements must be sorted.
# PROCEDURE :
First we to take an array i.e. p[] = {3,12,29,33,36,54,60,61,92,98}
Consider a  variable to iterate the elements in array i.e. ”s” and also find the mid value i.e. mid =(0+n)/2 or (first + last)/2, where n is index of last element.
Now iterate the loop i.e.  for (s=0; s<=n; s++)
Case 1: Then if the key element is equal to mid value print “I” this is the position of key element.
Case 2 :If the mid value is greater than key element than first = mid -1
Case 3: If the mid value is less than key element than first = mid +1
This will be continued until key element is found or until search space exhausted.
INPUT :
           12
                  92
                   33
OUTPUT:
               1
                8
                 4


