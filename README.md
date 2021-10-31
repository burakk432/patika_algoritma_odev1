# patika algoritma ödevi 1

Video ve notlarda "insertion sort" diye anlatılan, 
ama aslında "selection sort" olan algoritma ödevi:

[22,27,16,2,18,6]

0. [ ], [22, 27, 15, 2, 18, 6]
1. [2], [27, 15, 22, 18, 6]
2. [2, 6] , [15, 22,18, 27]
3. [2, 6, 15] , [18, 22, 27]
4. [2, 6, 15, 18] , [22, 27]
5. [2, 6, 15, 18, 22], [27]
6. [2, 6, 15, 18, 22, 27]


Worst Case: O(n^2)	 (İç içe 2 loop olduğundan dolayı quadratic time complexity)
Average Case : θ(n^2) 
Best Case : Ω(n^2) 

18 = average case

[7,3,5,8,2,9,4,15,6]

0. [ ], [7, 3, 5, 8, 2, 9, 4, 15, 6]
1. [2], [3, 5, 8, 7, 9, 4, 15, 6]
2. [2, 3] , [5, 8, 7, 9, 4, 15, 6]
3. [2, 3, 4] , [8, 7, 9, 5, 15, 6]
4. [2, 3, 4, 5] , [7, 9, 8, 15, 6]
