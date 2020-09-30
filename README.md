# Hactoberfest
for hactoberfest
IN THIS WE WILL ADD SOME BASIC C,C++ PROGRAMS FOR BEGINNERS

1.Program to print hello world

#include<stdio.h>
int main(){
  printf("Hello World!!!");
  return 0;
}

2.Program to find factorial of a number using recursion
// FACTORIAL OF A NUMBER USING RECURSION(CALL BY VALUE)
#include<stdio.h>
int factorial(int num){
    if (num==0 || num==1)
    {
        return 1;
    }else
    {
        return  num*factorial(num-1);
    }
    
    
}
int main(int argc, char const *argv[])
{
    int n;
    printf("please enter the number:");
    scanf("%d",&n);
    printf("The factorial of the number is: %d",factorial(n));
    return 0;
}

