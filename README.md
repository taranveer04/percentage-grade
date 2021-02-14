
#include<stdio.h>
#include<conio.h>
main()
{
	int business, science,it, medical, nonmedical, sum;
	float per;
	printf("enter business marks = ");
	scanf("%d",&business);
	printf("enter science marks = ");
	scanf("%d",&science);
	printf("enter it marks = ");
	scanf("%d",&it);
	printf("enter medical marks = ");
	scanf("%d",&medical);
	printf("enter nonmedical marks = ");
	scanf("%d",&nonmedical);	
	sum= business+ science+ it+ medical+ nonmedical;
	printf("\nsum of marks =%d",sum);
	per=(float)sum/5;
	printf("\nPercentage of marks=%f",per);
	if (per >=90&&per<=100)
	{
	printf("\n Grade=A \n100 percent scholorship");
	}
	else if ((per>=80)&&(per<90))
	{
	printf("\n Grade= B \n75 percent scholorship");
	}
	else if((per>=70)&&(per<80))
	{
	printf("\n Grade= C \n 50 percent scholorship");
	}
	else
	{
	printf("\n not eligible for scholorship");
	}
}
