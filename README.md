#include <iostream>
using namespace std;
int main() {
    cout << "Would you like to continue game arshdeep and bikram?" << endl;
  char input; // candy crush or vice city
    cin >> input;//candy crush

    switch (input) { // arshdeep and bikram are very exited to play game
        case 'Y': //case y for yes they are ready to battle with each other
      case 'y':// they want to start this game from their laptop
            break; // this battle has finished 
      case 'N':  // arshdeep and bikram will not play again as they are going for studying
        cout<< "quit"<< endl;
               //they will choose to do home work
            break;
        default: //default case
            cout<< "he has no time" << endl ;//they want to play this intrested game however they want to go their home for studying
      }        
    return 0;
  }
