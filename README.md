<!-- [A6-2] (https://prezi.com/p/edit/-xdwv8fik5xk/) -->

<!--
## ![A6-2](https://nimbus-screenshots.s3.amazonaws.com/s/4f4a634adf0c7c85fc178d5c682b7302.png) -->

## Open the "q2.cpp"

Complete the following functions to do the following works:

The program will take three user numbers and then finds the min number among these values. We need to develop three functions as follows:

1. get three user numbers

void getInput(int &n1, int &n2, int &n3);  
// In this function, ask the user three values and assign them to the parameter n1, n2, and n3

2. find the minimum number and return to the main function.

int  findMin(int n1, int n2, int n3);  
// The return value : the min among n1, n2 and n3.

3. Print the results

void printResult(int n1, int n2, int n3, int min);  
// Print out the results with the original numbers and the minimum value

4. Here is the part of the main function

// In main( ), call the functions  
getInput(n1, n2, n3);  
min = findMin(n1, n2, n3);  
printResult(n1, n2, n3, min);
