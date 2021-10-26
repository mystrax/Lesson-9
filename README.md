# Lesson-9
  
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

    int input;
      cout << "Type number 1 or 2\n";
      cin >> input;
      while (input == 1) {
        cout << "You have entered number 1" << endl;
      }while (input == 2)
        cout << "You have entered number 2" << endl;
      return 0;
