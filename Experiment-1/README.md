# Experiment No: 1
## Implementation of Binary search algorithm using Divide & Conquer method.

Title: Implementation of Binary search algorithm using Divide & Conquer method.

Theory/Description:
Binary search can be performed on a sorted array. In this approach, the index of an element x is determined if the element belongs to the list of elements. If the array is unsorted, linear search is used to determine the position.
In this algorithm, we want to find whether element x belongs to a set of numbers stored in an array numbers[]. Where l and r represent the left and right index of a sub-array in which searching operation should be performed.

<img width="495" alt="image" src="https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/57ec698a-0714-4aa7-9268-32d1d5c0a9cc">

### Example :
In this example, we are going to search element 63.

![image](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/9ad3e1ab-66ef-4d6e-900e-904a597ef06c)

Program:
#include <stdio.h>

int main()
{
int c, first, last, middle, n, search, array[100];

printf("Enter number of elements\n"); scanf("%d",&n);

printf("Enter %d integers\n", n); for (c = 0; c < n; c++)

scanf("%d",&array[c]);

printf("Enter value to find\n"); scanf("%d", &search);

first = 0; last = n - 1;

middle = (first+last)/2;

while (first <= last) {

if (array[middle] < search) first = middle + 1;

else if (array[middle] == search) {
 
printf("%d found at location %d.\n", search, middle+1);

break;
}

else

last = middle - 1; middle = (first + last)/2;
}
if (first > last)

printf("Not found! %d isn't present in the list.\n", search); return 0;

}

### Conclusion( must include analysis of program)or output:
![Screenshot (393)](https://github.com/22bdo10074/Semester_4-Practicals/assets/142095565/c79ebf14-2fa5-4237-8707-18a42ab41c53)


### Analysis : 
Linear search runs in O(n) time. Whereas binary search produces the result in O(log n) time. Let T(n) be the number of comparisons in worst-case in an array of nelements.
Hence,T(n)={0	fn=1 T(n/2)+1	otherwise
Using this recurrence relation T(n)=(logn) Therefore, binary search uses O(logn)time.








