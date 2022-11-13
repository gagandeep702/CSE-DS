
#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
#define SIZE 10

void push(int);
void pop();
void display();

int stack[SIZE], top=-1;
void main()
{
int value, choice;
while(1)
{
printf("\n\n ***** Menu******\n");
printf("1.Push\n2.Pop\n3.Display\n4.Exit\n");
printf("Enter Your Choice");
scanf("%d",&choice);
switch(choice)
{
case 1:printf("Enter the value to be inserted:");
       scanf("%d",&value);
       push(value);
       break;
case 2 :pop();
        break;
case 3:display();
break;
case 4: exit(0);
default:printf("\n Wrong Selection!!!!!!! Try Again !!!!");
}
}
}

void push(int value)
{
if(top==SIZE-1)
printf("Stack is full. Insertion not possible.....");
else{
top++;
stack[top]=value;
printf("\n Insertion Successful!!");
}
}

void pop()
{
if(top==-1)
printf("Stack is Empty.. Cannot delete");
else{
printf("Deleted:%d",stack[top]);
top--;
}
}

void display()
{
if(top==-1)
printf("Stack is Empty...");
else{
int i;
printf("\nStack elements:\n");
for(i=top;i>=0;i--)
printf("%d\n",stack[i]);
}
}
