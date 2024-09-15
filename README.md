//WPS TO REPRESENT ALL OPPS COCEPT

#include <iostream>
#include <string>
using namespace std;
class Animal {
    string name;
public:
    Animal(string n) : name(n) {}
};
class Dog : public Animal {
public:
    Dog(string n) : Animal(n) {}
};
class Cat : public Animal {
public:
    Cat(string n) : Animal(n) {}
};
int main() {
    Dog myDog("Buddy");
    Cat myCat("Whiskers");
    return 0;
}

//WPS FOR ARRAY

#include<iostram>
using namespace std;

int main() {
    int arr[10],n;
    cin>>n;
    for(int i=0;i<n;i++){
        cin>>arr[i];
}
cout<<arr[i];
for(int i=0;i<10;i++){
    if(arr[i]%2==0){
        cout<<"even"<<arr[i];
        else
        cout<<"nothing";
    }}
    return 0;
}



