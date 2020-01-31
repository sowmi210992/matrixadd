#include<stdio.h>
int main()
{
    int a[5][5],b[5][5],rows,cols,i,j,c[5][5];
    printf("enter rows,cols:");
    scanf("%d%d",&rows,&cols);
    printf("enter 1 array");
    for(i=0;i<rows;i++)
    {
        for(j=0;j<cols;j++)
        {
            scanf("%d",&a[i][j]);
        }
    }
    printf("enter 2 array");
    for(i=0;i<rows;i++)
    {
        for(j=0;j<cols;j++)
        {
            scanf("%d",&b[i][j]);
        }
    }
     for(i=0;i<rows;i++)
    {
        for(j=0;j<cols;j++)
        {
            c[i][j]=a[i][j]+b[i][j];
        }
    }
     for(i=0;i<rows;i++)
    {
        for(j=0;j<cols;j++)
        {
           printf("matrixadd");
            printf("%d ",c[i][j]);
            
        }
        printf("\n");
    }
    
}
output:
enter rows,cols;2
2
enter 1 array:
1 2
3 4
enter 2 arrays:
1 2
3 4
matrixadd
2 4
6 8
