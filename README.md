# Myfile
#include <iostream>
#include<string>
using namespace std;

int main()
{
    string name;
    
    cout << "Please enter your full name: ";
    getline(cin,name); 
    
    if (name == "harrish")
        cout << "I love you, Harrish!" << endl;
    else if (name == "harrish pubalan")
        cout << "I love you, my chello!" << endl;
    else if (name == "Harrish")
        cout << "Yes, baby, I love you, pa!" << endl;
    else if (name == "Harrish Pubalan")
        cout << "Yes, my dear purusha HARRISH PUBALAN!" << endl;
    else
        cout << "You are not the person I was expecting. GET LOST!" << endl;
    
    return 0;
}
