Bubble Sort:

Original array
[8 6 7 5 3 0 9 ]


i = 0
j = 0
array[0] = 8
array[1] = 6
8 swaps with 6 since it's greater
Result: [6 8 7 5 3 0 9 ]

i = 0
j = 1
array[1] = 8
array[2] = 7
8 swaps with 7 since it's greater
Result: [6 7 8 5 3 0 9 ]

i = 0
j = 2
array[2] = 8
array[3] = 5
8 swaps with 5 since it's greater
Result: [6 7 5 8 3 0 9 ]

i = 0
j = 3
array[3] = 8
array[4] = 3
8 swaps with 3 since it's greater
Result: [6 7 5 3 8 0 9 ]

i = 0
j = 4
array[4] = 8
array[5] = 0
8 swaps with 0 since it's greater
Result: [6 7 5 3 0 8 9 ]

i = 0
j = 5
array[5] = 8
array[6] = 9
8 stays since it's less than 9
Result: [6 7 5 3 0 8 9 ]

i = 1
j = 0
array[0] = 6
array[1] = 7
6 stays since it's less than 7
Result: [6 7 5 3 0 8 9 ]

i = 1
j = 1
array[1] = 7
array[2] = 5
7 swaps with 5 since it's greater
Result: [6 5 7 3 0 8 9 ]

i = 1
j = 2
array[2] = 7
array[3] = 3
7 swaps with 3 since it's greater
Result: [6 5 3 7 0 8 9 ]

i = 1
j = 3
array[3] = 7
array[4] = 0
7 swaps with 0 since it's greater
Result: [6 5 3 0 7 8 9 ]

i = 1
j = 4
array[4] = 7
array[5] = 8
7 stays since it's less than 8
Result: [6 5 3 0 7 8 9 ]

i = 1
j = 5
array[5] = 8
array[6] = 9
8 stays since it's less than 9
Result: [6 5 3 0 7 8 9 ]

i = 2
j = 0
array[0] = 6
array[1] = 5
6 swaps with 5 since it's greater
Result: [5 6 3 0 7 8 9 ]

i = 2
j = 1
array[1] = 6
array[2] = 3
6 swaps with 3 since it's greater
Result: [5 3 6 0 7 8 9 ]

i = 2
j = 2
array[2] = 6
array[3] = 0
6 swaps with 0 since it's greater
Result: [5 3 0 6 7 8 9 ]

i = 2
j = 3
array[3] = 6
array[4] = 7
6 stays since it's less than 7
Result: [5 3 0 6 7 8 9 ]

i = 2
j = 4
array[4] = 7
array[5] = 8
7 stays since it's less than 8
Result: [5 3 0 6 7 8 9 ]

i = 2
j = 5
array[5] = 8
array[6] = 9
8 stays since it's less than 9
Result: [5 3 0 6 7 8 9 ]

i = 3
j = 0
array[0] = 5
array[1] = 3
5 swaps with 3 since it's greater
Result: [3 5 0 6 7 8 9 ]

i = 3
j = 1
array[1] = 5
array[2] = 0
5 swaps with 0 since it's greater
Result: [3 0 5 6 7 8 9 ]

i = 3
j = 2
array[2] = 5
array[3] = 6
5 stays since it's less than 6
Result: [3 0 5 6 7 8 9 ]

i = 3
j = 3
array[3] = 6
array[4] = 7
6 stays since it's less than 7
Result: [3 0 5 6 7 8 9 ]

i = 3
j = 4
array[4] = 7
array[5] = 8
7 stays since it's less than 8
Result: [3 0 5 6 7 8 9 ]

i = 3
j = 5
array[5] = 8
array[6] = 9
8 stays since it's less than 9
Result: [3 0 5 6 7 8 9 ]

i = 4
j = 0
array[0] = 3
array[1] = 0
3 swaps with 0 since it's greater
Result: [0 3 5 6 7 8 9 ]

i = 4
j = 1
array[1] = 3
array[2] = 5
3 stays since it's less than 5
Result: [0 3 5 6 7 8 9 ]

i = 4
j = 2
array[2] = 5
array[3] = 6
5 stays since it's less than 6
Result: [0 3 5 6 7 8 9 ]

i = 4
j = 3
array[3] = 6
array[4] = 7
6 stays since it's less than 7
Result: [0 3 5 6 7 8 9 ]

i = 4
j = 4
array[4] = 7
array[5] = 8
7 stays since it's less than 8
Result: [0 3 5 6 7 8 9 ]

i = 4
j = 5
array[5] = 8
array[6] = 9
8 stays since it's less than 9
Result: [0 3 5 6 7 8 9 ]

i = 5
j = 0
array[0] = 0
array[1] = 3
0 stays since it's less than 3
Result: [0 3 5 6 7 8 9 ]

i = 5
j = 1
array[1] = 3
array[2] = 5
3 stays since it's less than 5
Result: [0 3 5 6 7 8 9 ]

i = 5
j = 2
array[2] = 5
array[3] = 6
5 stays since it's less than 6
Result: [0 3 5 6 7 8 9 ]

i = 5
j = 3
array[3] = 6
array[4] = 7
6 stays since it's less than 7
Result: [0 3 5 6 7 8 9 ]

i = 5
j = 4
array[4] = 7
array[5] = 8
7 stays since it's less than 8
Result: [0 3 5 6 7 8 9 ]

i = 5
j = 5
array[5] = 8
array[6] = 9
8 stays since it's less than 9
Result: [0 3 5 6 7 8 9 ]

i = 6
j = 0
array[0] = 0
array[1] = 3
0 stays since it's less than 3
Result: [0 3 5 6 7 8 9 ]

i = 6
j = 1
array[1] = 3
array[2] = 5
3 stays since it's less than 5
Result: [0 3 5 6 7 8 9 ]

i = 6
j = 2
array[2] = 5
array[3] = 6
5 stays since it's less than 6
Result: [0 3 5 6 7 8 9 ]

i = 6
j = 3
array[3] = 6
array[4] = 7
6 stays since it's less than 7
Result: [0 3 5 6 7 8 9 ]

i = 6
j = 4
array[4] = 7
array[5] = 8
7 stays since it's less than 8
Result: [0 3 5 6 7 8 9 ]

i = 6
j = 5
array[5] = 8
array[6] = 9
8 stays since it's less than 9
Result: [0 3 5 6 7 8 9 ]



———————————————

Insertion Sort
Original array
[73 114 111 110 109 97 110 ]


i = 1
j = 1
array[1] = 114
array[0] = 73
114 stays since it's greater than 73
Result: [73 114 111 110 109 97 110 ]

i = 2
j = 2
array[2] = 111
array[1] = 114
111 swaps with 114 since it's less
Result: [73 111 114 110 109 97 110 ]

i = 2
j = 1
array[1] = 111
array[0] = 73
111 stays since it's greater than 73
Result: [73 111 114 110 109 97 110 ]

i = 3
j = 3
array[3] = 110
array[2] = 114
110 swaps with 114 since it's less
Result: [73 111 110 114 109 97 110 ]

i = 3
j = 2
array[2] = 110
array[1] = 111
110 swaps with 111 since it's less
Result: [73 110 111 114 109 97 110 ]

i = 3
j = 1
array[1] = 110
array[0] = 73
110 stays since it's greater than 73
Result: [73 110 111 114 109 97 110 ]

i = 4
j = 4
array[4] = 109
array[3] = 114
109 swaps with 114 since it's less
Result: [73 110 111 109 114 97 110 ]

i = 4
j = 3
array[3] = 109
array[2] = 111
109 swaps with 111 since it's less
Result: [73 110 109 111 114 97 110 ]

i = 4
j = 2
array[2] = 109
array[1] = 110
109 swaps with 110 since it's less
Result: [73 109 110 111 114 97 110 ]

i = 4
j = 1
array[1] = 109
array[0] = 73
109 stays since it's greater than 73
Result: [73 109 110 111 114 97 110 ]

i = 5
j = 5
array[5] = 97
array[4] = 114
97 swaps with 114 since it's less
Result: [73 109 110 111 97 114 110 ]

i = 5
j = 4
array[4] = 97
array[3] = 111
97 swaps with 111 since it's less
Result: [73 109 110 97 111 114 110 ]

i = 5
j = 3
array[3] = 97
array[2] = 110
97 swaps with 110 since it's less
Result: [73 109 97 110 111 114 110 ]

i = 5
j = 2
array[2] = 97
array[1] = 109
97 swaps with 109 since it's less
Result: [73 97 109 110 111 114 110 ]

i = 5
j = 1
array[1] = 97
array[0] = 73
97 stays since it's greater than 73
Result: [73 97 109 110 111 114 110 ]

i = 6
j = 6
array[6] = 110
array[5] = 114
110 swaps with 114 since it's less
Result: [73 97 109 110 111 110 114 ]

i = 6
j = 5
array[5] = 110
array[4] = 111
110 swaps with 111 since it's less
Result: [73 97 109 110 110 111 114 ]

i = 6
j = 4
array[4] = 110
array[3] = 110
110 stays since it's equal to 110
Result: [73 97 109 110 110 111 114 ]

i = 6
j = 3
array[3] = 110
array[2] = 109
110 stays since it's greater than 109
Result: [73 97 109 110 110 111 114 ]

i = 6
j = 2
array[2] = 109
array[1] = 97
109 stays since it's greater than 97
Result: [73 97 109 110 110 111 114 ]

i = 6
j = 1
array[1] = 97
array[0] = 73
97 stays since it's greater than 73
Result: [73 97 109 110 110 111 114 ]
