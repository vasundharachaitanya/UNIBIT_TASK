# UNIBIT_TASK
Explanation for this code
1.Initialize an empty dictionary or hash table to store the visited numbers and their indices.

2.Iterate through the given array, and for each element at index i:
a. Calculate the complement value (target value minus the current element) as complement = target - array[i].
b. Check if the complement value exists in the dictionary. If it does, you have found a pair of elements whose sum equals the target value.

If the complement value exists, add the pair of indices to the result array as [array[i], array[complement_index]].
c. Add the current element to the dictionary with its index as the value.
3.Merge the resulting array of pairs into a single array.

4.Sort the merged array in ascending order.

5.Double the target value.

6.Initialize an empty list to store the combinations.

7.Iterate through the merged array, and for each element at index i:
a. Calculate the complement value (double the target value minus the current element) as complement = double_target - merged_array[i].
b. Check if the complement value exists in the dictionary. If it does, you have found a combination of elements whose sum equals the double target value.

If the complement value exists, add the combination of elements to the result array as [merged_array[i], merged_array[complement_index]].
c. Add the current element to the dictionary with its index as the value.
8.Return the resulting combinations.

