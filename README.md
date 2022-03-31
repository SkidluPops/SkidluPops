- 👋 Hi, I’m @SkidluPops
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
#include<stdio.h>
#include<conio.h>
int main()
{
	
char com[30];
int i=2, a=0;
printf("\nEnter Comment:");
gets(com);
if(com[0]==',')
{
	if(com[1]==',*')
	printf("\n It is a Comment");
	else if(com[1]=='*')
	{
		for(i=2;i<=30;i++)
		{
			if(com[i]=='*'&&com[i+1]=='/')
			{
				printf("\n It is a comment");
				a = 1;
				break;
				}
				else
				continue;
				}
				if(a==0)
				printf("\n It is not a comment");
				}
				else
				printf("\n It is not a comment");
				}
				else
				printf("\n It is not a comment");
				getch();
				}
	
<!---
SkidluPops/SkidluPops is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
