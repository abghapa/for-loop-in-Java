# for-loop-in-C++
a little intro about for loop in C++


# countdown using a for loop
##include <iostream>
using namespace std;

int main ()
{
  for (int n = 10; n > 0; n--) { 
  // starts with n = 10, and decreases until n is no longer bigger than 0
    cout << n << ", "; // print out every number
  }
  cout << "Happy New Year!!!"; // we are done!!!
}
