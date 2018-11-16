Add your answers to the Algorithms exercises here.

**Exercise I**
a) O(n), increments by n^2
2) O(n^3), first 3 for loops depend on n, the last for loop depends on k, no n-s, the last loop is constant.
3) O(n)

**Exercise II**:

some thoughts about eggs and breakings
-they all break at one point
-we can use the egg again, if it does not break
-we don't use the egg any more if it does break
-if did not break at one floor, it will not break if we go down 1 floor
-if it breaks on 1 floor, above that floor will break for sure

1. we make our first attempt on n'th floor.
2. if it breakes, we try the remaining floors one by one f-1
In worst case, we will try n times (we have n "numbers of floors)
3. if it does not break, we go up 1 floor (f+(f-1)).
4. if this egg will not break, we go up for the next 1 floor f+(f-1)+(f-2) etc
5. the sum of trials should be equal of the number of floors.
f+(f-1)+(f-2)+(f-3)etc+1 =n
f(f+1)/2=n

we have to consider also that the n could be 0 or 1.If we have 1 floor we need 1 drop, if we have 0 floor, we need 0 drop
for i in range(1, n+1):
eggFloor[i][1]=1
eggFloor[i][0]=0



