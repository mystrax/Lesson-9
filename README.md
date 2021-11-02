# Lesson-9
  
 Remain Positive
 
	 #include <iostream>
	using namespace std;

	int main()
	{

		double myNum=20;

		while (myNum>0) {
			myNum = myNum - 0.5;
			cout << myNum << endl;
		}

	}
 

 
 Reverse 9 times table

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
      int myNum= 117;
      while (myNum > 0) {
        myNum = myNum - 9;
        cout << myNum << endl;
      }
      return 0;
    }

Pointless Box

    #include <iostream>
    using namespace std;

    int main()
    {

      int input;
          cout << "Type number 1 or 2\n";
          cin >> input;
          while (input == 1) {
            cout << "You have entered number 1" << endl;
          }while (input == 2)
            cout << "You have entered number 2" << endl;
          return 0;
      }

 would you like to quit

    char input;
      do {
        cout << "Would you like to Quit? (Y/N)" << endl;
        cin >> input;
      } while ((input != 'Y') && (input != 'N'));	
      return 0;
		
brute force

	#include <iostream>
	using namespace std;
	int main()
	{
		string password = "246";
		string userInput;
		int x = 5;
		cout << "You will only have 5 attempts" << endl;


		while (x > 0)
		{
			cout << "Enter the pass code for the safe" << endl;
			cin >> userInput;
			if (userInput == password)
			{
				cout << "You have finally unlocked the safe" << endl;

				break;
			}
			else
				x--;
		}
		//to print the ran out of message only if the password was not found within 5 attempts
		if (x == 0)
		{
			cout << "You ran out of attempts" << endl;
		}
	}

pointless box

	#include <iostream>
	using namespace std;
	int main()
	{
	    cout << "Enter a number either 1 or 2\n";
	    int x; 
	    cin >> x;
	    while (x != 0 && x <= 2 && !cin.fail())
	    {
		if (x == 1)
		{
		    cout << "you have entered the number 1\n";
		}
		else
		{
		    cout << "you have entered the number 2\n";
		}

		cout << "Enter a number either 1 or 2\n";
		cin >> x;

	    }
	cout << "You did not enter the number 1 or 2";

	}
	
brute force I


	#include <iostream>
	using namespace std;
	int main()
	{
		string password = "246"; 
		string userInput;



		while (userInput != password)
		{
			cout << "Enter the pass code for the safe" << endl;
			cin >> userInput;

		}
		//to print the ran out of message only if the password was not found within 5 attempts
		cout << "You found the code";
	}
