## Program 11: Write a code using continue statement.
```
#include<stdio.h>
int main()
{
    int i;
    for(i=10;i<20;i++)
    {
        if(i==15)
        {
            continue;
        }
        printf("%d\n",i);
    }
    return 0;
}
```
**Output**:
```
           10
           11
           12
           13
           14
           15
           16
           17
           18
           19
 ```          
