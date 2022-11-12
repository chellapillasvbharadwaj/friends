# friends
Demo of two friends creating a website

We are two friends want to create a website
![](bharadwaj.jpg)


Hi, My name is Bharath Pusuluru.  
This is a sample code of bubble sort in `C`.    
```C
#include<stdio.h>
int main()
{
	int arr[20];
	int i,n,j,temp;
	
	printf("Enter size of array");
	scanf("%d",&n);
	
	for(i=0;i<n;i++)
	{
		scanf("%d",&arr[i]);
	}
	
	for(i=0;i<n-1;i++)
	{
		for(j=0;j<n-1-i;j++)
		{
			if(arr[j]>arr[j+1])
			{
				temp =arr[j];
				arr[j] = arr[j+1];
				arr[j+1] = temp;
				
			}
		}
	}
	for(i=0;i<n;i++)
	{
		printf("%d\n",arr[i]);
	}
}

```