# Statistics-with-Python
Basic Statistics for Python Developers


For data analysis, having a good understanding of applied statistics is essential. Here are some basic concepts in applied statistics that are particularly useful in data analysis for Python Developers. We will try to describe the necessary statistical methods first then we will apply Python libraries to implement the statistical result.




## Descriptive Statistics 

### 1. Mean
It is calculated by dividing the total number of observations by the sum of the observations. It can also be described as the sum divided by the count. In other words it is simply a mathematical average.

```
import statistics
# list of positive integer numbers
data1 = [1, 3, 4, 5, 7, 9, 2]
x = statistics.mean(data1)
# Printing the mean
print("Mean is :", x)
```
Output:

```
The mean is: 4.428571428571429
```


### 2. Median

(n+1)/2

It is the data set's middle value. It divides the data into two halves. If the number of items in the data set is odd, the center element is the median; otherwise, the median is the average of two center elements.

```
import statistics

from statistics import median
from fractions import Fraction as fr
data1 = (2, 3, 4, 5, 7, 9, 11)

# Printing the median of the above datasets
print("Median of data-set 1 is % s" % (median(data1)))
```
Output: 
```
Median of data-set 1 is 5
```
### 3. Mode
### 4. Standard Deviation
### 5. Range
### 6. Variance 






