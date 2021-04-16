#include<stdio.h>/*包含头文件*/
#include<math.h>/*包含各种函数的头文件*/
int main()/*定义主函数*/
{
	int a, b, c,f,x,n;/*定义整形变量*/
	double d;/*定义双精度变量*/
	int i,j;
	int y = 1;/*定义整形变量i,j,y*/
	scanf_s("%d", &i);/*通过让用户输入不同数字来进行不同种类的运算*/
	switch (i)/*运用switch case语句，输入对应的i值从而进行相应的运算*/
	{
	case 1:/*加法运算*/
			printf("Please input two numbers:");/*打印请输入两个数*/
			scanf_s("%d,%d", &a, &b);/*读入用户输入的两个数字*/
			c = a + b;/*将a+b的值赋值给c*/
			printf("%d+%d=%d", a, b, c);/*输出结果*/
				break;/*结束*/
	case 2:/*倒数运算*/
		printf("Please input one number:");/*打印请输入*/
		scanf_s("%d", &a);/*读入用户输入的数*/
		d = 1 / a;/*求倒数*/
		printf("%d的倒数为：%d", a, d);/*打印的倒数为*/
		break;/*结束*/
	case 3:/*求平方根运算*/
		printf("Please input one number:");/*在窗口打印:please input one number*/
		scanf_s("%d", &a);/*读入一个数*/
		d = sqrt(a);/*调用求平方根函数sqrt*/
		printf("%d的平方根为%d", a, d);/*打印的倒数为*/
		case 4:/*取余运算*/
			scanf_s("%d,%d", &a, &b);/*读入a,b*/
			x = a, n = b;
           printf("Please input two numbers:x=%d,n=%d",a,b);/*让用户输入两个数*/
             for(j=1;j<=n;j++)
{
	         y = x * y;/*累乘法*/
}
          printf("y=%d", y);/*打印出y的值*/
          break;
	}
