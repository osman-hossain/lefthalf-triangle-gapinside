<!--comments-->
_tr_ i~~a~~ `ngle` ~~Ha~~_lf_
---

<p>// write a programme that print triangle left half</p>  

```c
#include<stdio.h>
int main()
{
    while(1)
    {
        int num,row,col;
        printf("Enter the number : ");
        scanf("%d",&num);

        for(row=1; row<=num; row++)
        {
            for(col=1; col<=row; col++)
            {
                if(row==1 || row==num || col==1 || col==row)
                {
                    printf("* ");
                }
                else
                    printf("  ");
            }
            printf("\n");
        }
    }
}
```  
<image src="./images/lefthalf.png" width="500" title="lefthalf"/>

continue edit...

