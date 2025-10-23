# Module-4 Day-4 SEB
## AIM:
To write a C program to count the total number of words in a given string using For loop.

## For example:

## Program:
```c
#include<stdio.h>
int main(){
    char a[100];
    scanf("%[^\n]",a);
    int i,count=0;
    for(i=0;a[i]!='\0';i++){
        if(a[i-1]==' ' || a[i+1]=='\0'){
            count+=1;
        }
    }
    printf("%d",count);
    return 0;
}
```
## Result:
