Add your answers to the Algorithms exercises here.

I

a) O(n)

b) O(n^3)

c) O(n)

II

set groud floor to 0 and top floor to n

while ground floor is <= top floor
get the middle floor

if f breaks
set top floor to middle - 1
elif f doesn't break
set ground floor to middle + 1
else
return middle

O(n)
