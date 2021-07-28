#include<stdio.h>

int main()
{
	printf("%d\n", sizeof(char));//1
	printf("%d\n", sizeof(short));//2
	printf("%d\n", sizeof(int));//4
	printf("%d\n", sizeof(long));//4
	printf("%d\n", sizeof(long long));//8
	printf("%d\n", sizeof(float));//4
	printf("%d\n", sizeof(double));//8
	return 0;
}
#include<stdio.h>

int main()
{
	int num1 = 0;
	int num2 = 0;
	scanf_s("%d%d",&num1,&num2);//vs编译使用scanf_s替换scanf
	int sum=0;//注:空格没必要 = 与=一样//C语法规定变量要定义在当前代码块的最前端，vs没事
	sum = num1 + num2;
	printf("sum=%d\n",sum);
	return 0;
}
