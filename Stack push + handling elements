// Create a c++ program and push 3 different values into the stack 
// Print the top element, remove the top element and print the new top and remove then print all the remaining elements 

#include<iostream>
#include<stack>
using namespace std;

// do everything in the main function
// the top function returns the last value entered into the stack (the last age pushed)
// LIFO - last in, first out
int main(){
    stack<int> ages;

    ages.push(25);
    ages.push(18);
    ages.push(21);
    ages.push(22);
    ages.push(25);
    ages.push(24);

    cout << "The last age pushed: " << ages.top() << '\n';
    ages.pop();
    cout << "Top after calling pop function: " << ages.top() << '\n';
    cout << "Remaining elements: ";

    while(!ages.empty()){
        cout << ages.top() << ' ';
        ages.pop();

    }
    cout << '\n';
    return 0;

}


