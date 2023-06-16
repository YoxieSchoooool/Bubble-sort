# What is a Bubble sort?
A bubble sort is a simple sorting algorithm that works by seeing if the adjacent values are larger/smaller than the selected value, and swapping them accordingly

### It works in this order:
* Is the selected value a higher number than the value next to it?
* If it is a larger value, they will swap
* This repeats across the next pair of numbers until the end of the array
* This is a complete bubble sort
* Passes will be made until they are no longer needed



![Bubble sort example](https://res.cloudinary.com/practicaldev/image/fetch/s--STdcoqy9--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/asfmbhsv8q0r7ltfc2sk.gif "Bubble sort example")

# What about a merge sort?
Merge Sort is a Divide and Conquer algorithm. It divides input array in two halves, calls itself for the two halves and then merges the two sorted halves. The merge() function is used for merging two halves. The merge is key process that assumes that array and array are sorted and merges the two sorted sub-arrays into one. 

### How it works
* Splitting
  * The first list will be halved into two new lists
  * This is repeated until all lists have a single value
* Merging
   * The smallest items from adjacent lists are compared
   * Whichever is smaller goes into a new merged list first
   * This is repeated until a new list is formed from all of the split lists
   * One fully sorted merged list should remain

![Bubble sort example](https://www.learnsimpli.com/wp-content/uploads/2020/09/How-merge-sort-works.gif "Bubble sort example")



