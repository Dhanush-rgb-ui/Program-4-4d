# Module-4 Day-4 SEB
## AIM:
To write a C program to count the total number of words in a given string using For loop.

## For example:
<img width="297" height="107" alt="image" src="https://github.com/user-attachments/assets/f93498ae-bd64-444a-8660-5022e4c64b58" />

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
<img width="447" height="112" alt="image" src="https://github.com/user-attachments/assets/524fcae2-26d5-4597-8bc8-fe3b3dca405e" />
