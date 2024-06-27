#include <stdio.h>
void f2()
{
    printf("i am in function f2\n");
}
void f1()
{
    f2();
    printf("i am in function f1");
}
int main()
{
    f1();
    return 0;
}
