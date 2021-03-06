# epi-js

These are my current solutions to [Elements of Programming Interviews][1], written in Javascript and Typescript. I'm currently working on updating all solutions into Typescript.
A disjoint set of problems done in Python can be found here: [EPI-Py][46]

### How to run

After cloning the directory, prepare it with:

```bash
npm install
```

To run the included unit tests:

```bash
npm run test:watch
```

# Solutions

## Primitive Types

| Problem                             |    Test    |
| ----------------------------------- | :--------: |
| [Computing the parity of a word][2] | [tests][3] |

## Arrays and Strings

### Arrays

| Problem                                         |    Test     |
| ----------------------------------------------- | :---------: |
| [The Dutch national flag problem][4]            | [tests][5]  |
| [Compute the Spiral Ordering of a 2D Array][47] | [tests][48] |

### Strings

| Problem                                 |    Test     |
| --------------------------------------- | :---------: |
| [Interconvert Strings and Integers][49] | [tests][50] |
| [Replace and Remove][51]                | [tests][52] |

## Linked Lists

| Problem                     |    Test     |
| --------------------------- | :---------: |
| [Merge two sorted lists][6] | [tests][7]  |
| [Cycle Detection][53]       | [tests][54] |

## Stacks and Queues

### Stacks

| Problem                             |    Test    |
| ----------------------------------- | :--------: |
| [Implement a stack with max API][8] | [tests][9] |

### Queues

| Problem | Test  |
| ------- | :---: |


## Binary Trees

| Problem                         |    Test     |
| ------------------------------- | :---------: |
| [Traversal of binary trees][10] | [tests][11] |

## Heaps

| Problem                       |    Test     |
| ----------------------------- | :---------: |
| [Merging k sorted arrays][12] | [tests][13] |

## Searching

### Binary Search

| Problem                                       |    Test     |
| --------------------------------------------- | :---------: |
| [Finding the first element larger than k][14] | [tests][15] |

### Generalized Search

| Problem | Test  |
| ------- | :---: |


## Hash Tables

| Problem                                                        |    Test     |
| -------------------------------------------------------------- | :---------: |
| [Checking if the characters of string A can form string B][16] | [tests][17] |

## Sorting

| Problem                                         |    Test     |
| ----------------------------------------------- | :---------: |
| [Find the intersection of two sorted lists][18] | [tests][19] |

## Binary Search Trees

| Problem                            |    Test     |
| ---------------------------------- | :---------: |
| [Determine is a tree is a BST][20] | [tests][21] |

## Recursion

| Problem | Test  |
| ------- | :---: |


## Dynamic Programming

| Problem                                          |    Test     |
| ------------------------------------------------ | :---------: |
| [Find the edit distance between two strings][22] | [tests][23] |

## Greedy Algorithms and Invariants

| Problem | Test  |
| ------- | :---: |


## Graphs

| Problem            |    Test     |
| ------------------ | :---------: |
| [Solve a maze][24] | [tests][25] |

## Parallel Computing

| Problem | Test  |
| ------- | :---: |


## Design Problems

| Problem | Test  |
| ------- | :---: |


## Honors Class

| Problem | Test  |
| ------- | :---: |


# Structures and Algorithms

| Type                     |    Test     |
| ------------------------ | :---------: |
| [Binary Tree][26]        | [tests][27] |
| [Binary Search Tree][28] | [tests][29] |
| [Graph Search][30]       | [tests][31] |
| [Hashtable][32]          | [tests][33] |
| [Binary Heap][34]        | [tests][35] |
| [Linked List][36]        | [tests][37] |
| [Tree Node][38]          | [tests][39] |
| [Sorts][40]              | [tests][41] |
| [Trie][44]               | [tests][45] |

[1]: http://elementsofprogramminginterviews.com
[2]: src/ch04-ptypes/p04-01.ts
[3]: src/ch04-ptypes/p04-01.spec.ts
[4]: src/ch05-arrays/p05-01.ts
[5]: src/ch05-arrays/p05-01.spec.ts
[6]: src/ch07-linkedLists/p07-01.ts
[7]: src/ch07-linkedLists/p07-01.spec.ts
[8]: src/ch08-stacksAndQueues/p08-01.js
[9]: src/ch08-stacksAndQueues/p08-01.spec.js
[10]: src/ch09-bTrees/p09-05.js
[11]: src/ch09-bTrees/p09-05.spec.js
[12]: src/ch10-heaps/p10-01.js
[13]: src/ch10-heaps/p10-01.spec.js
[14]: src/ch11-searching/p11-02.js
[15]: src/ch11-searching/p11-02.spec.js
[16]: src/ch12-hashtables/p12-09.js
[17]: src/ch12-hashtables/p12-09.spec.js
[18]: src/ch13-sorting/p13-05.js
[19]: src/ch13-sorting/p13-05.spec.js
[20]: src/ch14-bst/p14-01.js
[21]: src/ch14-bst/p14-01.spec.js
[22]: src/ch15-recur/p15-11.js
[23]: src/ch15-recur/p15-11.spec.js
[24]: src/ch18-graphs/p18-01.js
[25]: src/ch18-graphs/p18-01.spec.js
[26]: src/library/binaryTree.js
[27]: src/library/binaryTree.spec.js
[28]: src/library/BST.js
[29]: src/library/BST.spec.js
[30]: src/library/graph.js
[31]: src/library/graph.spec.js
[32]: src/library/hashtable.js
[33]: src/library/hastable.spec.js
[34]: src/library/heap.js
[35]: src/library/heap.spec.js
[36]: src/library/linkedList.ts
[37]: src/library/linkedList.spec.ts
[38]: src/library/node.ts
[39]: src/library/node.spec.ts
[40]: src/library/sorts.js
[41]: src/library/sorts.spec.js
[42]: src/library/suffixTree.js
[43]: src/library/suffixTree.spec.js
[44]: src/library/trie.js
[45]: src/library/trie.spec.js
[46]: https://github.com/Nigelmnz/epi-py
[47]: src/ch05-arrays/p05-18.ts
[48]: src/ch05-arrays/p05-18.spec.ts
[49]: src/ch06-strings/p06-01.ts
[50]: src/ch06-strings/p06-01.spec.ts
[51]: src/ch06-strings/p06-04.ts
[52]: src/ch06-strings/p06-04.spec.ts
[53]: src/ch07-linkedLists/p07-03.ts
[54]: src/ch07-linkedLists/p07-03.spec.ts
