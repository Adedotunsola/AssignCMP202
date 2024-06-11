## Step 1

Check if d is 0 no rotation is needed, exit the algorithm.

## Step 2

If d is greater than the array length, find the remainder when d is divided by arr.length.

## Step 4

Loop d times

## Step 5

Store the first element of the array in a temporary variable temp.

## Step 6

Loop through the array elements from index 1 to arr.length - 1:

## Step 7

Shift the current element one position to the left by assigning the value of the element at the next index (j + 1) to the current element (arr[j]).

## Step 8

Place the saved first element (temp) at the end of the array by assigning it to the last index (arr[arr.length - 1]).

## Step 9

Print the original array and the rotated array
