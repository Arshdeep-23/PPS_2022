## Program 16: Write a code using switch ststement.
```
#include<stdio.h>
int main()
{
	char a;
	printf("Enter no.:");
	scanf("%d",&a);
	switch (a)
	{
	case(1):
	printf("FAN ON");
	break;
	case(2):
	printf("LIGHT ON");
	break;
	case(3):
	printf("BULB ON");
	break;
	case(4):
	printf("AC ON");
	break;
	
	default:
	printf("Sorry wrong IP");		
	}
	return 0; 
}
```
**Output**:
```
Enter no.:2
LIGHT ON
```
