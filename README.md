# Lec 10 Codes



//FOR LOOP

For Loop Example 

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 0; x < 10; x++) {
            cout << "X is " << x << "\n"; 
        }
    }
                                

Countdown

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
  


//NESTED LOOPS

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



THE FOR LOOP EXERCISES


Exercise: Nested For Loop

Descending Stars, Seven Lines

    #include <iostream>
    using namespace std;
    int main()
    {

        for (int i = 1; i <= 7; i++) {
            for (int j = i; j <= 7; j++) {
                cout << "*";
            }
            cout << endl;
        }
    }
    
    
Rising Stars, Five Lines



Rising and Falling Stars




Exercise: For Loop

Cubes



Find the 9s


