+ [Divide and conquer](/dsa/techniques/divide_conquer.md)
+ [Sorting](/dsa/problems/sorting.md)
+ [Randomize](/dsa/techniques/randomization.md)

## Quicksort

1. Randomly select a pivot called p
2. Move values smaller than p to its left in the array and values bigger than p
   to is right in the array
3. Recursively continue with both subparts

The last step works since pivot p ends at its sorted position so we can threat
left and right subarrays as the same problem

