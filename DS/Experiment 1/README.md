#AIM OF THE EXPERIMENT: Writing binary search program by using iterative functions (non recursive functions).
#BINARY SEARCH: This is a search algorithm that finds the position of a target value within a sorted array by comparing the target value to the middle element of the array.
#PROCEDURE:
1.we have to take the given array which consists of 10 elements i.e. a[i] = {3,12,29,33,36,54,60,61,92,98}.
2. The first element position is considered as “I” which is “0” and the last element position is “n” which is “9”.
3. In binary search we will compare the key element to the mid positioned element of the array.
  i.e. Mid = (i + n)/2
4.In the given array mid value is (0 + 9)/2 =4.5 and ignoring the decimal value we will take the position as 4th and the element present at 4th is 36 .
5.We will use loop iteration process if the key element position is equal to the given mid position element then the output will be element found at 4th position (mid position in this array).
6.If the key element is not equal to the mid element then there are two ways to get the output
        1: If the key element is < than the mid position element then      i = 0 and n = mid - 1. And the same loop iteration continues until we get the position of the given element.
        2: If the key element is > than the mid position element then i = mid + 1 and n = 9.
7.Given key elements are 12,92,33.
8. our first key element is 12 so the mid position is 4th and the element is 36, which is > than 12 therefore i = 0 and n = mid – 1 i.e. 3 and now the mid value changes to (0 + 3)/2 = 1.5 and we will be considering it as the position 1 and at position 1 element is = 12 so output is “element found at 1”.
9. 2nd key element is 92 and mid element is 36, which is < than 92 so the i = mid + 1and n = 9 i=5 therefore (5+9)/2 = 7 and at 7th position element is 61 < 92 so I = mid + 1 and n = 9,(8+9)/2 = 8.5 = 8 and the output is “element found at 8”.
10.3rd key element is 33 and 33 < 36(mid element),n = mid -1 and i = 0 and the loop continues until the output is “element found at 3”
#INPUT:
12 92 33
#OUTPUT:
“element found at 1”
“element found at 8”
“element found at 3”.      
For key 12
![output](binaryiterative12.png)
For key 92
![output](binaryiterative92.png)
For key 33
![output](binaryiterative33.png)
