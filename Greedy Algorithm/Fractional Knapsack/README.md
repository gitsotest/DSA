# Fractional Knapsack Problem
## Maximum Value of the Loot
### Problem Introduction
A thief finds much more loot than his bag can fit. Help him to find the most valuable combination
of items assuming that any fraction of a loot item can be put into his bag.
### Problem Description
#### Task
The goal of this code problem is to implement an algorithm for the fractional knapsack problem.
#### Input Format. 
The first line of the input contains the number n of items and the capacity W of a knapsack.
The next n lines define the values and weights of the items. The i-th line contains integers v<sub>i</sub> and w<sub>i</sub>—the value and the weight of i-th item, respectively.
#### Constraints. 
1 ≤ n ≤ 10<sup>3</sup> , 0 ≤ W ≤ 2·10<sup>6</sup> ; 0 ≤ v<sub>i</sub> ≤ 2·10<sup>6</sup> , 0 < w<sub>i</sub>≤ 2·10<sup>6</sup> for all 1 ≤ i ≤ n. All the numbers are integers.
#### Output Format. 
Output the maximal value of fractions of items that fit into the knapsack. The absolute
value of the difference between the answer of your program and the optimal value should be at most
10<sup>−3</sup> . To ensure this, output your answer with at least four digits after the decimal point (otherwise your answer, while being computed correctly, can turn out to be wrong because of rounding issues).
#### Sample 1.
##### Input:
``` 
3 50
60 20
100 50
120 30 
```

##### Output:
`180.0000`

To achieve the value 180, we take the first item and the third item into the bag.
#### Sample 2.
##### Input:
```
1 10
500 30
```
##### Output:
`166.6667`

Here, we just take one third of the only available item.
