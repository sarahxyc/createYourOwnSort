# createYourOwnSort

## Intro
Our prompt was to create a new method to sort user-inputted numbers from smallest to greatest besides the bubbling method we programmed the day before. 

## Table of Contents
1. How it works
2. How we came up with it
3. Efficiency compared to the sort we did yesterday
4. Pros/cons of our method
5. Who did what
6. Conclusion

## 1. How it works
Our code first asks the user to input how many numbers they would like in the array, and then uses a for loop to initialize each value in the array. Then, in one loop, it utilizes a nested loop to go through the array to find the smallest value and place it at the beginning. The loop repeats until all of the numbers have been sorted. Finally, the array is printed outside of the loop.

## 2. How we came up with it
We came up with our algorithm by thinking about how we would sort numbers manually. We realized that finding the smallest number and moving it to the beginning would make it easier to organize the rest of the numbers. We decided to repeat this process for each position in the array until all the numbers were sorted from smallest to largest. 

## 3. Efficiency compared to the sort we did yesterday
Our selection sort algorithm is more efficient than bubble sort in terms of swapping numbers. Bubble sort repeatedly compares two numbers next to each other and swaps them if they are in the wrong order, while selection sort finds the smallest number and moves it directly to its correct position. This means selection sort generally requires fewer swaps. However, both methods still require many comparisons, especially when sorting a large amount of numbers. Bubble sort can also be faster when the numbers are already sorted if it is programmed to stop when no swaps are needed.

## 4. Pros/cons of our method
One advantage of our selection sort algorithm is that it is relatively simple to understand and implement using basic loops, arrays, and if statements. It also requires fewer swaps than bubble sort because it finds the smallest number in the unsorted section and moves it directly to its correct position, rather than repeatedly swapping numbers next to each other. Another advantage is that it sorts the numbers within the original array, so we do not need to create another array to store the sorted numbers. Our method also works with different types of integers, including positive numbers, negative numbers, and duplicates. However, one disadvantage is that it still requires many comparisons, especially when sorting a large number of inputs. The algorithm must repeatedly search through the remaining numbers to find the smallest value, even if most of the numbers are already in the correct order. Unlike bubble sort, which can be programmed to stop early when no swaps are needed, our selection sort algorithm continues checking the remaining numbers even if the array is already sorted. This makes our method less efficient when working with arrays that are already sorted or nearly sorted.

## 5. Who did what
We figured out how to sort the numbers together. Kayla coded the new algorithm.
Kayla wrote the 2, 3, and 4. Sarah wrote the intro, 1, 5, and 6.

## 6. Conclusion
We created a new method to sort user-inputted numbers from least to greatest in an array; we chose this method because it seemed the most feasible. Our method, in which we repeatedly loop to find the smallest number in the array and move it to the beginning, is more efficient than the bubble sort method we coded the day before, especially for larger arrays. Our code requires fewer swaps than the bubble sort method, but it still requires many swaps, and does not stop checking even until after all of the numbers are already sorted.
