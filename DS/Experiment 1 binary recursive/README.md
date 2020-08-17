# AIM OF THE EXPERIMENT:  To write a binary search program using recursive function.
#BINARY SEARCH: To find a key element in an given array in which the elements must be sorted.
#RECURSIVE FUNCTIONS: This basis of recursion is functions is to make the task simple and that the functions doesn’t make further calls.
#PROCEDURE:
1.Unlike iterative recursive doesn’t repeat the loop either it does call functions and make the code easy and make it effective .
2.First we to take an array i.e. a[] = {3,12,29,33,36,54,60,61,92,98}
3.Consider ”i“ variable to iterate the elements in array i.e. ”a” and also find the mid value i.e. mid =(0+n)/2 or (first + last)/2, where n is index of last element. (Since i = 0 for the first element). 
4.Now iterate the loop i.e.  for (i=0; i<=n; i++)
5.Case 1: Then if the key element is equal to mid value print “I” this is the position of key element.
 Case 2 :If the mid value is greater than key element than first = mid -1
 Case 3: If the mid value is less than key element than first = mid +1
6.For the first key given 36 the mid value is = (0 + 9)/2 = 4.5 =~ 4 and element at position 4 is 36 and it is equal to the first key element.
7.For the 2nd key given 92 mid value is 36<92 so I changes to mid + 1 and n remains same now the I = 5 and n = 9 now loop iterates to right and again mid position is (5+9)/2 = 7 and 7th element is 61<92 so the loop iterates right and I =8 and n =9 so the mid =(8+9)/2 = 8 and 8th element is 92 = key element so the output is 8
8.For the 3rd key given 33 mid value is 36>33 so I remains same and n = mid -1 now I = 0 and n = 3 mid = (0+3)/2 = 1.5 = 1 and 1st element is 12 and 12<33 so i= mid +1 =2 and n=3 and mid= (2+3)/2 = 2 , 2nd element is 29<33 and I = mid+1 = 3 and n =3 therefore the key element is in 3rd position.
This will be continued until key element is found or until search space exhausted.
#INPUT:
       36 92 33
#OUTPUT:
         4
         8
         3
![Screenshot (41)](https://user-images.githubusercontent.com/69639140/90410080-915b1280-e0c7-11ea-8f0b-713053eca938.png)
![Screenshot (42)](https://user-images.githubusercontent.com/69639140/90410094-94560300-e0c7-11ea-8433-10f0d494fb79.png)
![Screenshot (43)](https://user-images.githubusercontent.com/69639140/90410103-95873000-e0c7-11ea-9931-625853832767.png)
![Screenshot (44)](https://user-images.githubusercontent.com/69639140/90410151-a0da5b80-e0c7-11ea-91a0-0a1d29049aff.png)

