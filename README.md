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

Some counting (in progress)

• Write a program that counts up from 0 to 50 in increments of 1.

    #include <iostream>
    using namespace std;
    int main()
    {

        for (int x = 50; x >= 1; x--)
        {
            cout << x << endl;
            if (x == 1)
                cout << "eyy!\n";
        }
    }

• Write a program that counts down from 50 to 0 in decrements of 1.

    
    
• Write a program that counts up from 30 to 50 in increments of 1.
 
    
    
• Write a program that counts down from 50 to 10 in decrements of 2.

    
    
• Write a program that counts up from 100 to 200 in increments of 5.

    

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


Iterate through a word (in progress)




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
    
    
Rising Stars, Five Lines (in progress)



Rising and Falling Stars (in progress)




Exercise: For Loop

Cubes (in progress)



Find the 9s (in progress)


