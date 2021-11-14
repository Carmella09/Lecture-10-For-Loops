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
      for (int x = 10; x >= 1 ; x--){
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

Some counting 

• Write a program that counts up from 0 to 50 in increments of 1.
	
    #include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 0; x < 51; x++)
        {
            cout << x << endl;
        }
        cout << endl;
     }

• Write a program that counts down from 50 to 0 in decrements of 1.

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 50; x >= 0; x--)
        {
            cout << x << endl;
        }
        cout << endl;
    }
    
• Write a program that counts up from 30 to 50 in increments of 1.
 
    #include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 30; x < 51; x++)
        {
            cout << x << endl;
        }
    } 
    
• Write a program that counts down from 50 to 10 in decrements of 2.

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 50; x > 11; x = x - 2)
        {
            cout << x << endl;
        }
    }
    
• Write a program that counts up from 100 to 200 in increments of 5.

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 100; x < 201; x = x + 5)
        {
            cout << x << endl;
        }
    } 

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


Iterate through a word 

	#include <iostream>
	#include <string>
	using namespace std;
	int main()
	{
		for (int x = 0; x < 4; x++)
		{
			string myWord = "ARSH";
			cout << myWord.at(x) << endl;
		}
	}


Exercise: Nested For Loop

Seven Stars, Seven Lines

    #include <iostream>
    using namespace std;
    int main()
    {

        for (int i = 0; i < 7; i++) 
	{
            for (int j = 0; j < 7; j++) 
	    {
                cout << "*";
            }
            cout << endl;
        }
    }



//THE FOR LOOP EXERCISES


Exercise: Nested For Loop

Descending Stars, Seven Lines

    #include <iostream>
    using namespace std;
    int main()
    {

        for (int i = 1; i <= 7; i++) 
	{
            for (int j = i; j <= 7; j++) 
	    {
                cout << "*";
            }
            cout << endl;
        }
    }
    
    
Rising Stars, Five Lines

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int i = 1; i <= 5; i++)
        { 
            for (int j = 1; j <= i; j++)
            {
                cout << "*"; 
            }
            cout << endl; 
        }

    }


Rising and Falling Stars 

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int i = 1; i <= 5; i++)
        { 
            for (int j = 1; j <= i; j++)
            {
                cout << "*"; 
            }
            cout << endl; 
        }


        for (int i = 1; i <= 5; i++) 
        {
            for (int j = i; j <= 5; j++) 
            { 
                cout << "*"; 
            }
            cout << endl; 
        }

    }

Exercise: For Loop

Cubes 

	#include <iostream>
	using namespace std;
	int main()
	{
		int n;
		cout << "To find the cube of the number, you must enter a number: ";
		cin >> n;
		for (int x = 1; x <= n; x++)
		{
			cout << "\nNumber: " << x;
			cout << " Cube: " ;
			int y = x;
			y = y * y * y;
			cout << y;
		}
	}

Find the 9s 

	#include <iostream>
	using namespace std;
	int main()
	{
		int s = 0;
		for (int x = 100; x <= 200; x++)
		{
			if (x % 9 == 0)
			{
				cout << "Number: " << x << endl;
				s = s + x;
			}
		}
		cout << "\nSum: " << s << endl;
	}
