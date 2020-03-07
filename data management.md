

- Data types: scalars, vectors, matrices, lists, dataframes/tables

- Checking and Changing Types 
- Geting help
---
Importing external data
|Data format | Description | R function |
| ------------- |:-------------| -----|
|RData|the R data format - created using R software| ```load()```|
|csv |comma separated file | ```read.csv()```|
|txt |Text in tabular format|```read.table()```|
|xls and xlsx |Excel file formats | use excel packages eg ```readxl::read_excel()```|
|other formats: sav, etc | SPSS, etc | use _foreign_ package |
---

Building blocks of statistical and modeling operations 
- Operations
  - Arithmetics: ```+,-,*,/,^```
  - Logical: ```!, >,<,>=,<=,!=```

- Basic functions
|Function| Purpose|
| ------------- | -----|
|sum(x) |Sums the elements in x|
|prod(x)| Product of the elements in x|
|max(x) |Maximum element in x|
|min(x)| Minimum element in x|
|range(x) |Range (min to max) of elements in x|
|length(x) |Number of elements in x|
|mean(x) |Mean (average value) of elements in x.|
|median(x) |Median (middle value) of elements in x|
|var(x) |Variance of elements in x|
|sd(x) |Standard deviation of element in x|
|cor(x,y) |Correlation between x and y|
|quantile(x,p) |The pth quantile of x|
|cov(x,y) |Covariance between x and y |

- Combined basic functions
|Function| Purpose|
| ------------- | -----|
|summary(x) |Minimun, maximum, median, mean, quartiles 1 and 3 and number of missing values|
|fivenum(x)| Minimun, maximum, quartiles 1 and 3 and median|

_Statistical mode is not available in base R_

---