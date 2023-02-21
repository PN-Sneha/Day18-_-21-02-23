#include<stdio.h>
main()
{
	int num,temp,rem,rev=0;
	printf("Enter the number:");
	scanf("%d",&num);
	temp=num;
	while(num!=0)
	{
		rem=num%10;
		rev=rem+(rev*10);
		num=num/10;
	}
	if(rev==temp)
	printf("Given number %d is a Palindrome",temp);
	else
	printf("Given number %d is not a Palindrome",temp);
	return 0;
}
