### Jump search

Jump search algorithm, also called as block search algorithm. Only sorted list of array or table can alone use the Jump search algorithm. In jump search algorithm, it is not at all necessary to scan every element in the list as we do in linear search algorithm. We just check the R element and if it is less than the key element, then we move to the R + R element, where all the elements between R element and R + R element are skipped. This process is continued until R element becomes equal to or greater than key element called boundary value. The value of R is given by R = sqrt(n), where n is the total number of elements in an array. Once the R element attain the boundary value, a linear search is done to find the key value and its position in the array. It must be noted that in Jump search algorithm, a linear search is done in reverse manner that is from boundary value to previous value of R.

#### Jump search
![](http://www.stoimen.com/blog/wp-content/uploads/2011/12/jump-search-fig-1.png)