# L10


For Loop

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 0; x < 10; x++) {
            cout << "X is " << x << "\n"; 
        }
    }
                                

For Loop

    #include <iostream>
    using namespace std;
    int main()
    {

      for (int x = 10; x >= 1 ; x--)
      {
        cout << x << endl;
      if (x == 1)
        cout << "Time to Lift off!\n\n";
      }
    }
  
  
Nested Loops
  
      #include <iostream>
    using namespace std;
    int main()
    {

      for (int i = 0; i < 5; i++){
        for (int j = 0; j < 5; j++) {
          cout << "*";
        }
        cout << endl;
      }
    }


Nested Loops

      #include <iostream>
    using namespace std;
    int main()
    {

      for (int i = 1; i <= 5; i++){
        for (int j = i; j <= 5; j++) {
          cout << "*";
        }
        cout << endl;
      }
    }
    
    
//EXERCISE BREAK

Exercise: For Loop

Odd or Even

    #include <iostream>
    using namespace std;
    int main() 
    {
      for (int x = 20; x <= 24; x++) 
      {
        if (x % 2 == 0) 
        {
          cout << x << " is an Odd" << endl;
        }
        else 
        {
          cout << x << " is an Even" << endl;
        }
       }
    }

Exercise: Nested For Loop

Seven Stars, Seven Lines

    #include <iostream>
    using namespace std;
    int main()
    {

        for (int i = 0; i < 7; i++) {
            for (int j = 0; j < 7; j++) {
                cout << "*";
            }
            cout << endl;
        }
    }
