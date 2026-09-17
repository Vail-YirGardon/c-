  2026/9/13，顺利运行hello world
  2026/9/14知识点总结：
int a，声明整数a
float b，声明小数b
＋-*/
转移序列
转移序列：显示变量int类型（不可变量）%d，scanf类型（可变量）%d,&变量名称
注意 "%d" 符号完整
占位符int：%d    float：%f
经ds辅助成功做到教程视频里的效果
/*表示注释*/，//表示注释
#define 定义等价
格式化输入/输出错误类型：占位符与参数不匹配，参数多/少于占位符，数据类型不匹配。成功运行教学视频p2中所有内容
---
  2026/9/16知识总结
int型和float型结果是float型
%取余结果整数，优先运算加（）
int main下a=a+1，a++/++a（a的值+1）
 1代表正确，0代表错误
关系运算符>,<,>=,<=        6<7是1，6>7是0
判等运算符==，!=(不等于)    5==5是1，5！=5是0
逻辑运算符!(逻辑非)，&&(逻辑与)，||(逻辑或)
if/else后只跟一个有效语句，两个语句用{括成一个整体}
级联：else if（   ）;
*project name:project1*/
//变量命名不能数字开头



#include<stdio.h>
#include<stdio.h>

int a=7,b=5,c=9;

#define p  3.14

int main(void)
{
	a=b<c?5:6;
	

	printf("a的数为:");
	printf("%d",a);
 
	return 0;
}
num;



int main(void)
{
	
	printf("请输入一个数:");
	scanf("%d",&num);
	if (num%2==0)
	   { num=num*5;
	      printf("这是一个偶数");
	     }
	else 
	   {num=num*3;
	      printf("这是一个奇数");
	    }
	
	
	return 0;
}
#include<stdio.h>
int num;

int main(void)
{

	printf ("请输入您的成绩:");
	scanf("%d",&num);
	
	swcith(num)
	{
	    case 0:
		case 1:
	    case 2:
		case 3:
		case 4:
		case 5:
		printf("您的成绩不合格");
		break
		case 6:
		printf("您的成绩合格");
		break
		case 7:
	    case 8:
	    case 9:
		printf("您的成绩优秀");
		break
		case 10:
		printf("您的成绩满分");
		break
     	default:
		printf("您的成绩有误");	
	}
	
	return 0;
}
