# Teste
Programa de palavras palíndromas
#include <iostream>
#include <string>
using namespace std;
 
int main(){
    string word;
    string letra;
    cout<<"Enter a word: ";
    cin>>word;
   
    for (int i = word.length() -1; i>= 0; i--){
        cout << letra[i];
           
    if (word == letra)
        cout<<" Is a palindrome.";
        else
         cout<<" Is not palindrome.";
    }
    cout << endl;
 
    return 0;
   
}
