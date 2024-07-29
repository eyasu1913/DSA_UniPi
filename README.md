# Algorithms and Data Structures (for Data Science)

* Teacher: [Rossano Venturini](http://pages.di.unipi.it/rossano)
* CFU: 9
* Period: Second semester
* Language: English
* Classroom: [here](https://classroom.google.com/u/1/c/NjYxNTg1NzIyODc1)  (code: 7ucbcgh)
* Lectures schedule: Tuesday 9:00-11:00 (Aula Fib C), Wednesday 9:00-11:00 (Aula Fib C), and Friday 9:00-11:00 (Aula Fib C).
* Question time: After lectures or by appointment

## Goals and opportunities

The course introduces basic data structures and algorithmic techniques that allow students to solve computational problems on the most important data types, such as sequences, sets, trees, and graphs.

The lectures will be complemented by an intensive activity in laboratory.
Students will experiment with algorithms and data structures by writing their own implementations or by using third-party libraries.

The goal of the class is to enable students to design and implement efficient algorithms, choosing the most appropriate solutions in their future projects.

### Syllabus

- Introduction and basic definitions: algorithm, problem, instance.

- Computational complexity analysis of algorithms.

- Sorting: Mergesort, Quicksort and Heapsort.

- Searching: Binary Search, Binary Search Tree, Trie, and Hashing.

- Algorithms on Trees: representation and traversals.

- Algorithms on Graphs: representation, traversals, and most important problems.

- External memory model: sorting and searching.

## Exam

| Type | Date | Room | Note|
| ------------- | ------------- | ------------- | ----- |
| Lab | 02/09/2024 14:00 | Google Meet | Please send your solutions to me by 30/08/2024. **Important:**  Please Cut&Paste your solutions to this [Jupyter Notebook](Lab/Solutions_NAME_SURNAME.ipynb) and **send me just this file** with your name and surname on its filename. Please read the very important note below. |
| Theory | 05/09/2024 14:00 | Aula Fib C |  |


**Very important!** You are allowed to verbally discuss solutions (e.g., a strategy to solve a problem) with other students, **BUT** you have to implement all the solutions yourself. Thus, sharing implementations or implementing a solution with others is strictly **forbidden**.

## References
*   Introduction to Algorithms,  3rd Edition, Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein, The MIT Press, 2009 ([Amazon](http://www.amazon.com/Introduction-Algorithms-3rd-Thomas-Cormen/dp/0262033844/ref=sr_1_1?s=books&ie=UTF8&qid=1443160441&sr=1-1&keywords=introduction+to+algorithms)) [CCLR]
*   Algorithms, 4th Edition, Robert Sedgewick, Kevin Wayne, Addison-Wesley Professional, 2011 ([Amazon](http://www.amazon.com/Algorithms-4th-Edition-Robert-Sedgewick/dp/032157351X/ref=pd_sim_14_2?ie=UTF8&refRID=1A2NFN935EST0ZQARB6H&dpID=51UDgHU9z9L&dpSrc=sims&preST=_AC_UL160_SR130%2C160_)) [RS]
*   Algorithms, Sanjoy Dasgupta, Christos Papadimitriou, Umesh Vazirani, McGraw-Hill, 2006\. ([Amazon](http://www.amazon.com/Algorithms-Sanjoy-Dasgupta/dp/0073523402)) [DPZ]

## Lectures
| Date | Lecture | References | Material |
| -------------: | :------------- | :------------- | :------------- |
| 20/02/2024 | Introduction to analysis of algorithms.| CCLR Sect. 2.1 | [Notes next 3 lectures](Notes/Analysis22.pdf)|
| 21/02/2024 | Insertion Sort: Correctness and analysis.| CCLR Sect. 2.2 | [VisuAlgo Sorting](https://visualgo.net/en/sorting) |
| 23/02/2024 | Insertion Sort: Correctness and analysis.| CCLR Sect. 2.2 | [VisuAlgo Sorting](https://visualgo.net/en/sorting) |
| 27/02/2024 | Selection Sort: Correctness and analysis.|  | [Selection Sort vs Insertion Sort ](Notes/L01_Insertion_Sort_vs_Selection_Sort.ipynb) and [VisuAlgo Sorting](https://visualgo.net/en/sorting)|
| 28/02/2024 | Divide and Conquer. Merge Sort. | CCLR Sect. 2.3  | [VisuAlgo Sorting](https://visualgo.net/en/sorting) and  [Notes next 3 lectures](Notes/Mergesort22.pdf) |
| 01/03/2024 | **Laboratory**: Basic sorting algorithms | | [Jupyter Notebook](Lab/Lecture_01/L01_Basic_Sorting_no_sols.ipynb) **Mandatory exercises** |
| 05/03/2024 | Divide and Conquer. Merge Sort. (contd) Binary search.| CCLR Sect. 2.3,  CCLR Sect 3.1 | [VisuAlgo Sorting](https://visualgo.net/en/sorting) |
| 06/03/2024 | QuickSort. Best and worst cases. No average time analysis. | CCLR Sects 7.1, 7.2, and 7.3. | [VisuAlgo Sorting](https://visualgo.net/en/sorting) and [Notes next 2 lectures](Notes/Quicksort22.pdf) |
| 08/03/2024 | **Laboratory**: MergeSort and QuickSort. | | [Jupyter Notebook](Lab/Lecture_02/L02_Sorting_no_sols.ipynb) **Mandatory exercises** | 
| 12/03/2024 | QuickSort. Best and worst cases. No average time analysis. | CCLR Sects 7.1, 7.2, and 7.3. | [VisuAlgo Sorting](https://visualgo.net/en/sorting) and [Notes next 2 lectures](Notes/Quicksort22.pdf) |
| 13/03/2024 | Lower Bound for sorting in the comparison model. | CCLR Sect. 8.1 |[Notes](Notes/Lowerbound22.pdf) |
| 15/03/2024 | **Laboratory**: Applications of sorting (I). | | [Jupyter Notebook](Lab/Lecture_03/L03_Sorting_Applications_Greedy_Algorithms_no_sols.ipynb) **Mandatory exercises** | 
| 19/03/2024 | Sorting in linear time: Counting Sort. | CCLR Sect. 8.2 | [VisuAlgo Sorting](https://visualgo.net/en/sorting). [Notes next 2 lectures](Notes/LinearTimeSorting22.pdf)| 
| 20/03/2024 | Sorting in linear time: Radix Sort. | CCLR Sect. 8.3.| [VisuAlgo Sorting](https://visualgo.net/en/sorting) |
| 22/04/2024 | Python best practices. | | |
| 03/04/2024 | Python best practices. | | |
| 05/04/2024 | Python best practices. | | |
| 08/04/2024 | Python best practices. | | |
| 10/04/2024 | Dictionary problem with Hashing.| CCLR Sect. 11.1, 11.2, and 11.4 (no analysis) | [Notes](Notes/Hashing22.pdf) |
| 12/04/2024 | **Laboratory**: Hashing. | | [Jupyter Notebook](Lab/Lecture_04/L04_Hashing_no_sols.ipynb) **Mandatory exercises** |
| 16/04/2024 | QuickSelect. Priority queues: Heap. | CCLR Sect. 9.1, 9.2 and CCLR Ch. 6 | [Notes next 3 lectures](Notes/Heap.pdf) |
| 17/04/2024 | Priority queues: Heap. | CCLR Ch. 6 | [VisuAlgo Heap](https://visualgo.net/en/heap?slide=1) | 
| 19/04/2024 | **Laboratory**: Hashing: Applications.  | | [Jupyter Notebook](Lab/Lecture_05/L05_Hashing_Applications_no_sols.ipynb) **Mandatory exercises** |
| 23/04/2024 | Binary Search tree. | CCLR Sect. 12.1, 12.2, and 12.3  | [Visualgo BST](https://visualgo.net/en/bst) | [Notes for next two lectures](Notes/Bst.pdf) |
| 24/04/2024 | Binary Search tree. | CCLR Sect. 12.1, 12.2, and 12.3  | [Visualgo BST](https://visualgo.net/en/bst) |  | 
| 26/04/2024 | **Laboratory**: Applications of sorting (II). | | [Jupyter Notebook](Lab/Lecture_06/L06_Sorting_Applications_II_no_sols.ipynb) **Mandatory exercises** |
| 30/04/2024 | Exercises: Visits of a tree. |  | [Notes next 2 lectures](Notes/Trees.pdf) | |
| 03/05/2024 | **Laboratory**: Binary Search Tree.  | | [Jupyter Notebook](Lab/Lecture_07/L07_Binary_Search_Tree_no_sols.ipynb) **Mandatory exercises** |
| 07/05/2024 | Exercises: Visits of a tree. |  | | | 
| 08/05/2024 | Graphs: representations and BFS. |CCLR Sect. 22.1 and 22.2 (no proofs) | [Notes next 2 lectures](Notes/Graphs.pdf) | 
| 10/05/2024 | Graphs: DFS. |CCLR Sect. 22.3 (no proofs) | [Graph representations](https://visualgo.net/en/graphds) and [BFS/DFS](https://visualgo.net/en/dfsbfs) |
| 14/05/2024 | Exercises | [Notes](Notes/Exam20210610_sol.pdf) |
| 15/05/2024 | Exercises | [Notes](Notes/Exam20210723_sol.pdf)|
| 17/05/2024 | **Laboratory**: Graphs.  | | [Jupyter Notebook](Lab/Lecture_08/L08_Graphs_with_NetworkX_no_sols.ipynb) **Mandatory exercises** |

