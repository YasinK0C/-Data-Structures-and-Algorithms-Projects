<h1>The given sequence is: [22, 27, 16, 2, 18, 6]</h1>

**In the first step**, 27 is compared with 22 and since 27 is greater than 22, their positions are swapped: [22, 27, 16, 2, 18, 6]

**In the second step**, 16 is compared with 27 and 22 respectively and since 16 is less than 22, its position is swapped with 22: [16, 22, 27, 2, 18, 6]

**In the third step**, 2 is compared with 27, 22, and 16 respectively and since 2 is less than 16, its position is swapped with 16: [2, 16, 22, 27, 18, 6]

**In the fourth step**, 18 is compared with 27, 22, and 16 respectively and since 18 is greater than 16, its position is swapped with 22: [2, 16, 18, 27, 22, 6]

**In the fifth step**, 6 is compared with 27, 22, 18, and 16 respectively and since 6 is less than 16, its position is swapped with 16: [2, 6, 18, 27, 22, 16]

---

**As a result, the array is sorted**: [2, 6, 16, 18, 22, 27]

The Big-O notation of this sorting algorithm is **O(n^2)**, which means it requires the square of the number of elements to be sorted in the worst case.

---

After the series is sorted, the number 18 we are looking for is in the middle, so it is included in the **Average case**.

---

<h1>[7,3,5,8,2,9,4,15,6]</h1> 

<h3>The first 4 steps of the sequence according to the Selection Sort</h3>

1. Find the minimum element in the array and swap it with the first element. The minimum element in the array is 2, so we swap it with the first element: [2, 3, 5, 8, 7, 9, 4, 15, 6]

2. Find the minimum element in the subarray starting from the second element and swap it with the second element. The minimum element in the subarray [3, 5, 8, 7, 9, 4, 15, 6] is 3, so we swap it with the second element: [2, 3, 5, 8, 7, 9, 4, 15, 6]

3. Find the minimum element in the subarray starting from the third element and swap it with the third element. The minimum element in the subarray [5, 8, 7, 9, 4, 15, 6] is 4, so we swap it with the third element: [2, 3, 4, 8, 7, 9, 5, 15, 6]

4. Find the minimum element in the subarray starting from the fourth element and swap it with the fourth element. The minimum element in the subarray [8, 7, 9, 5, 15, 6] is 5, so we swap it with the fourth element: [2, 3, 4, 5, 7, 9, 8, 15, 6]