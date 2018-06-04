"Perhaps the most important principle for the good algorithm designer is to refuse to be content"


Karatsuba multiplication

operating on data are so fast the time can be seen as free -- time needed almost same as reading the input data -- Eg: sorting algorithm.


different ds corresponding to different queries.




compared with selection, insertion, bubble sorts;
selection: O(n^2)
find current min/max, exchange with the current position

insertion: O(n^2)
for current, insert into the sorted part;

bubble:  O(n^2)
compare neighbour pair, exchange; repeat except last element.


Merge Sort:

merge: get head of two children array,, copy smaller one to the original array

running time: number of operations (as a debugger, how many times you click to run the programme)


Principles:
1. worst-case analysis
    average-case/benchmarks
    - need domain knowledge, what inputs will be more common etc.
2. ignore lower order terms/ constant factors
3. asymptotic analysis: focus on large input
    - in fine tuned version merge sort, there will be a threshold, below the threshold it will use small constant factor sorting such as insertion. (constant factor is meaningful)


fast: worst-case running time grows slowly with input sizes -> close to O(n) as possible.