# binary-search
In Computer Science, Binary Search (Half-Interval Search) is a Search Algorithm to find a specific element located in an Array (ONLY works with Sorted Arrays). Binary Search is advantageous over a standard Linear Search because it searches faster and more efficiently due to what some developers call as “Dividing and Conquering.”

Instead of searching an array at index 0, 1, 2, 3, 4, and so on like we do in a For Loop, Binary Search allows us to divide our search in half each time we look for a target value.

We define a middleIndex or midpoint from the element in the middle of the array (Divide) to see if our target value is greater than or less than the middleIndex or midpoint. Depending on if the target value is greater than or less than the middleIndex, we can remove the left or right of our array from our search (Conquer).
