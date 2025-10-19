# Delete Element from an Array (C Program)

## Description

This C program demonstrates how to delete an element from a specific index of an array.
After deleting, the subsequent elements are shifted to the left to fill the gap.

---

## How It Works

1. Read the number of elements `n`.
2. Input `n` integers into the array.
3. Read the index `idx` of the element to be deleted.
4. Shift elements from `idx + 1` to the end one position to the left.
5. Decrease the size of the array by 1.
6. Print the updated array.

---

### Example Input

5
10 20 30 40 50
3

### Example Output

10 20 30 50

## Algorithm Steps

1. Read integer `n`.
2. Declare an array `a[n]`.
3. Input `n` elements into the array.
4. Read the index `idx` of the element to delete.
5. For `i = idx` to `n-2`, shift elements → `a[i] = a[i + 1]`.
6. Decrease `n` by 1.
7. Print the updated array.

