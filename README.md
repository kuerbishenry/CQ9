# CQ9

Mini max sum
time complexity- O(n log n) due to collections.sort(), the time complexity of the rest of code is O(n) bc the for loops run to arr.size()
space compelxity- O(1) constant space 

Weighted uniform strings
time complexity- O(m*n) in the second for loop there is a .contains check which has a time complexity of O(n) and it is nested inside of
a for loop that runs for queries.size() (m) 
space complexity- O(n+m) the results list stores an element for each queries (m) and the weights list stores a weight for each character in the string, those combined give us the
O(n+m) time complexity
