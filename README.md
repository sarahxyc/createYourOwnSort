# createYourOwnSort

## Intro

## Table of Contents
1. How it works
2. How we came up with it
3. Efficiency compared to the sort we did yesterday
4. Pros/cons of our method
5. Who did what
6. Conclusion

## 1. How it works


## 2. How we came up with it
We came up with our algorithm by thinking about how we would sort numbers manually. We realized that finding the smallest number and moving it to the beginning would make it easier to organize the rest of the numbers. We decided to repeat this process for each position in the array until all the numbers were sorted from smallest to largest. 


## 3. Efficiency compared to the sort we did yesterday
Our selection sort algorithm is more efficient than bubble sort in terms of swapping numbers. Bubble sort repeatedly compares two numbers next to each other and swaps them if they are in the wrong order, while selection sort finds the smallest number and moves it directly to its correct position. This means selection sort generally requires fewer swaps. However, both methods still require many comparisons, especially when sorting a large amount of numbers. Bubble sort can also be faster when the numbers are already sorted if it is programmed to stop when no swaps are needed.

## 4. Pros/cons of our method
One advantage of our selection sort algorithm is that it is relatively simple to understand and implement using basic loops, arrays, and if statements. It also requires fewer swaps than bubble sort because it finds the smallest number in the unsorted section and moves it directly to its correct position, rather than repeatedly swapping numbers next to each other. Another advantage is that it sorts the numbers within the original array, so we do not need to create another array to store the sorted numbers. Our method also works with different types of integers, including positive numbers, negative numbers, and duplicates. However, one disadvantage is that it still requires many comparisons, especially when sorting a large number of inputs. The algorithm must repeatedly search through the remaining numbers to find the smallest value, even if most of the numbers are already in the correct order. Unlike bubble sort, which can be programmed to stop early when no swaps are needed, our selection sort algorithm continues checking the remaining numbers even if the array is already sorted. This makes our method less efficient when working with arrays that are already sorted or nearly sorted.

## 5. Who did what


## 6. Conclusion
