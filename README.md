# Assignment For AsIndiaInnovation

Question 1 : Used C++ Language.

<b>Approach1</b>
1. In this approach I used an array to keep track of numbers which are not present in n-1 elements.
2. First i declare an array with n+1 elements then fill all the entries of array with false (means element is not present).
3. Then i have taken each of n-1 elements and marks that entry(index) of array to be true (means element is present).
4. Then looping the array and printing that value which has false in it (It means it is not present in given n-1 elements).
5. Solving through this method i also applied constraint by making sure that no one hits same element twice or goes out of bound.

<b>Approach2</b>
1. In this approach I have taken sum of 1 to n number using n(n+1)/2.
2. Then i started subtracting each element of n-1 elements from the above sum.
3. After substracting all the elements from the above sum. The remaining value of sum will be the element which is not present in n-1 elements.
4. This method is more efficient.
5. In this method i have not check constraint i.e duplicates , range bounds . I assumed correct inputs according to constraints are given by user.
