Add your answers to the Algorithms exercises here.
a) I think it is O(n) because it only runs through once?

b) I think it is O(n^3) because it has a bunch of nested for-loops that increase each other?

c) I think it is O(n) because it ticks down at a linear pace?

II.
Start at the midpoint of _n_ and drop an egg, then drop an egg from the midpoint of the lower half if it breaks. If the egg from that midpoint breaks, divide that segment in half again and drop from the lower half, and repeat if it breaks.

If any of the eggs drop and don't break, then repeat the process on the upper half of the most recent segment instead of the lower half. Eventually you will find floor _f_. I think it's logarithmic. O(log n)