#include <iostream>
using namespace std;

#define size 10
int arr[size], top = -1;

bool isEmpty()
{
    if(top == -1) return true;
    else return false;
}

void push (int value)
{
    if(top == size-1)
    {
        cout << "stack is full" << endl;
    }
    else {
        arr[++top]=value;
    }
}

void pop()
{
    if(isEmpty())
    {
        cout << "Stack is empty" << endl;
    }
    else
    {
        top--;
    }
}

void show_top()
{
    if(isEmpty())
    {
        cout << "Stack is empty" << endl;
    }
    else
    {
        cout << "Element at top is: " << arr[top] << endl;
    }
}

void display()
{
    if(isEmpty())
    {
        cout << "Stack is empty" << endl;
    }
    else
    {
        for(int i = 0; i <= top; i++)
        {
            if (i > 0) cout << ", ";
            cout << arr[i];
        }
        cout << endl;

    }
}


int main()
{
    push(5);
    push(10);

    cout << "Stack elements: ";
    display();

    cout << "Top of the stack: ";
    show_top();

    pop();

    cout << "Stack elements after popping: ";
    display();

    return 0;
}
