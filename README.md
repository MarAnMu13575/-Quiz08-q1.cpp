# -Quiz08-q1.cpp
#include iostream>

using namespace std;

void newline(){

  cout<<endl;
}

int sumsquares_list (int z[5], int size) //primero las variables

{
  int a=0, i; //que son iguales
  
  for (i=0; i<6; i++)// sus características
  
  {
    a= a + (z[i]*z[i]); //que va a hacer
    
  }
    return a; //que regrese a esto
    
  }

  int main ()// la función
  
  {
    int list[5]; //numero de datos que se van a poner en la lista

    cout << "Hello people, I will ask you to give me numbers, ¿Ready?: " << endl;
    newline();
    cout << "Ok, Ok the first one:  ";
    cin >> list[0];
    newline();
    cout << "OOOOOOO look, the second one:   ";
    cin >> list[1];
    newline();
    cout << "We already finish it:  ";
    cin >> list[2];
    newline();
    cout << "Maybe one more time:  ";
    cin >> list[3];
    newline();
    cout << "And the last one:";
    cin >> list[4];
    newline();

    cout << "And now, the sum of the squares numbers that you gave me is: " << sumsquares_list(list,5);

    return 0;
  }
