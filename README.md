# Quicksort Pivots

in the lectures I only briefly mentioned strategies for determining a good pivot
for quicksort. The implementation on the slides simply picks the leftmost
element in the part of the array that we consider as a pivot. I also mentioned a
few other ways of picking a good pivot, e.g. randomly.

Median-of-three is also a good way of picking a pivot -- inspect the first,
middle, and last elements of the part of the array under consideration and
choose the median value. Using the probabilities for picking a pivot in a
particular part of the array (in the same way as we did on slide 34), argue
whether this method is more or less (or equally) likely to pick a good pivot
compared to simply choosing the first element. Assume that all permutations are
equally likely, i.e. the input array is ordered randomly.

Your answer must derive probabilities for choosing a good pivot and
quantitatively reason with them.

Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

I believe that the Median-of-Three is a better choice for getting a better pivot. I think this because based on statistics as the bell curve, when choosing the lefmost as the pivot there is a 68% chance that it is in the middle quartile of the random permutation. To keep it simple we can say that it has about 1/2 chance of being a good pivot. By using the median out of the left most, middle, and rightmost using the median of three we can increase the percentage of it being closer to the median just by having more data points that are likely to span values over the list. I dont know the percentage it would be unless i had the data myself but it will definatly be better still because of the median taken from the three numbers has a better chance of being closer to the middle than just a single number taken.

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
