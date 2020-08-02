# Cplusplus
## Initializer List in C++
[When do we use Initializer List in C++](https://www.geeksforgeeks.org/when-do-we-use-initializer-list-in-c/)<br>
[Constructor member initializer lists](https://www.learncpp.com/cpp-tutorial/8-5a-constructor-member-initializer-lists/)
## memset
```cpp
//for char array
char str[5];
memset(str, 'u', 5*sizeof(char));
memset(str, 'u', sizeof(str));

//for int array : we can just initiate 0 or -1
int test[10];
memset(test, -1, 10*sizeof(int));
memset(test, 0, sizeof(test));
```
[memset] (https://www.geeksforgeeks.org/memset-in-cpp/) <br>
