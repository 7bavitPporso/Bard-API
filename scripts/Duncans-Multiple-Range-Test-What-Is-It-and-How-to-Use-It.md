## Duncan's Multiple Range Test: What Is It and How to Use It?

  
# Duncan's Multiple Range Test: What Is It and How to Use It?
 
Duncan's Multiple Range Test (DMRT) is a statistical method for comparing the means of different groups after performing an analysis of variance (ANOVA). It is a post hoc test, which means that it is done after finding a significant difference among the groups. DMRT can help identify which specific groups have significantly different means from each other.
 
## duncanmultiplerangetestsoftwarefreedownload


[**Download File**](https://www.google.com/url?q=https%3A%2F%2Furluso.com%2F2tKBwP&sa=D&sntz=1&usg=AOvVaw3VWEDh8mpoe1zv5Uq8IcGL)

 
DMRT was developed by David B. Duncan as an alternative to Newman-Keuls test, which has a higher risk of making false positive errors (Type I errors). DMRT is more useful when comparing larger pairs of means, especially when they are arranged in a table. DMRT requires larger differences between means to be significant, which reduces the chance of finding differences that are not real.
 
To perform DMRT, you need to rank the group means from highest to lowest and compare them pairwise, starting from the highest and lowest means. For each pair of means, you need to calculate a critical value based on the standard error of the difference between means, the number of groups, and the degrees of freedom for the error term. You can find this critical value by looking up a q-table. If the difference between the means is greater than the critical value, then the means are significantly different. You can stop the comparison once you find a non-significant difference.
 
DMRT can be done by hand, but it is easier and faster to use a software program that can perform ANOVA and DMRT automatically. There are several software options available online, some of them are free and some are paid. For example, you can use Statistics How To[^1^], ResearchGate[^2^], or Docker Hub[^3^] to download or access DMRT software.
 
DMRT is a useful tool for analyzing data from experiments that involve multiple groups and testing hypotheses about their mean differences. However, it has some limitations and assumptions that you should be aware of before using it. For example, DMRT assumes that the data are normally distributed, have equal variances, and are independent. DMRT also does not control for the overall error rate across multiple comparisons, which means that it may still inflate the Type I error rate if you have too many groups or comparisons. Therefore, you should use DMRT with caution and check if your data meet the assumptions before applying it.

## How to Use a Q-Table for DMRT
 
A q-table is a table that shows the critical values for DMRT based on the number of groups and the degrees of freedom for the error term. You can find a q-table online or in a statistics textbook. To use a q-table, you need to follow these steps:
 
1. Find the number of groups (k) and the degrees of freedom for the error term (df) from your ANOVA output.
2. Locate the row that corresponds to your k value and the column that corresponds to your df value in the q-table.
3. The value at the intersection of the row and column is the q-value for your DMRT.
4. Multiply the q-value by the standard error of the difference between means (Ïd) to get the critical value for your DMRT.
5. Compare the critical value with the difference between means for each pair of groups. If the difference is greater than the critical value, then the means are significantly different.

Here is an example of a q-table:
  | k\df | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | |------|------|------|------|------|------|------|------|------| | 2    | 17.6 | 9.92 | 7.96 | 7.05 | 6.51 | 6.16 | 5.91 | 5.72 | | 3    | 18.5 | 10.6 | 8.53 | 7.56 | 6.99 | 6.61 | 6.35 | 6.14 | | 4    | 19   | 11   | 8.88 | 7.87 | 7.28 | 6.88 | 6.61 | 6.39 | | ...  | ...  | ...  | ...  | ...  | ...  | ...  | ...  | ...  |  
Suppose you have four groups with a df of 8 and a Ïd of 2.42. You would find the q-value for k = 4 and df = 8, which is 6.39. Then you would multiply it by Ïd to get the critical value:
 
critical value = q-value \* Ïd = 6.39 \* 2.42 = \*\*15.46\*\*
 
This means that any pair of means that have a difference greater than \*\*15.46\*\* are significantly different from each other.
 0f148eb4a0
