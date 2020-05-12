//
//  main.cpp
//  Project 3
//
//  Created by Truman Yee on 5/11/20.
//  Copyright © 2020 Truman Yee. All rights reserved.
//

#include <iostream>

using namespace std;

int askOpperation();

int addition = 1;
int subtraction = 2;
int division = 3;
int multiplication = 4;
int a;
int a1;
int b1;
int a2;
int b2;
int a3;
int b3;
int a4;
int b4;


int main()
{
    
    askOpperation ();
    return 0;
}

int askOpperation(){
    
    cout<< "What opperation do you want to use\n";
    cout<<"addition = 1\n";
    cout<<"subtraction = 2\n";
    cout<<"multiplication = 3\n";
    cout<<"division = 4\n\n";
    cin>> a;
    
    if (a == 1){
        
        
        
        cout<<"\nfirst addend\n";
        cin>> a1;
        cout<<"second addend\n";
        cin>> b1;
        cout<<"the answer is ";
        
        int sum = a1 + b1;
        
        cout<< sum<<endl<<endl;
        
  askOpperation ();
        
    }
    
    if (a == 2){
         
        
        
        cout<< "\nminuend\n";
        cin>> a2;
        cout<< "subtrahend\n";
        cin>> b2;
        cout<<"the answer is ";
        
        int difference = a2 - b2;
        
        cout<<difference<<endl<<endl;
        
   askOpperation ();
        
     }
    
    if (a == 3){
       
        
        cout<<"\nfirst factor\n";
        cin>> a3;
        cout<<"second factor\n";
        cin>> b3;
        cout<<"the answer is ";
        
        int product = a3 * b3;
        
        cout<<product<<endl<<endl;
        
  askOpperation ();
        
     }
    
    if (a == 4){
        
        
        cout<<"\ndividend\n";
        cin>> a4;
        cout<<"divisor\n";
        cin>>b4;
        cout<<"the answer is ";
        
        int quotient = a4 / b4;
        int remainder = a4 % b4;
        
        cout<< quotient;
        cout<<" remainder ";
        cout<< remainder<<endl<<endl;

          askOpperation ();
        
     }
    
    return 0;
}
