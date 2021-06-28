# c-path
学习情况
include <stdio.h>
include<string.h>
int main()
{
	int arr[10] = { 0 };//10个整形元素的数组
	int sz = 0;
	//10*sizeof(int) = 10
	printf("%d\n", sizeof(arr));
	//计算数组的元素个数
	//个数=数组总大小/每个元素的大小
	sz = sizeof(arr) / sizeof(arr[0]);
	printf("sz=%d\n", sz);
	//int a = 10;
	////sizeof 计算的是变量/类型所占空间的大小 单位是字节
	//printf("%d\n", sizeof(a));//4
	//printf("%d\n", sizeof(int));//4
	//printf("%d\n", sizeof a);//4
	return 0;
}