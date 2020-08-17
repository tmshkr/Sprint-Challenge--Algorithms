#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Time complexity: O(n) because n * n inside the while loop
   cancels out n * n in the while loop's condition


b) Time complexity: O(n log n) because the for loop runs n times,
   and the nested while loop runs log n times as j doubles each time


c) Time complexity: O(n) because it will recurse n times

## Exercise II

1. Throw an egg from the middle floor
2. If it breaks, the floor is either too high or the target floor (f)
   a. If we've visited the floor below and it didn't break, then the current floor is (f) and we're done!
   b. Otherwise, we can lower the upper bound (u) to the current level to reduce the number of floors
   c. Go to the floor midway between the upper bound (u) and the lower bound (l) to try again 
3. If it doesn't break, the floor is too low
   a. We can raise (l) to the current level in order to reduce the number of floors
   b. Go to the floor midway between the upper bound (u) and the lower bound (l) to try again

Runtime complexity: O(log n)
