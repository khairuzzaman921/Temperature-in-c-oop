# Temperature-in-c-oop


#include <iostream>
using namespace std;

// create a class
class temperature {
  // private data member
  private:
    float k;

  // public functions
  public:
    // getTemperature() function to get the Temperature
    void jaman() {
      cout << "Enter Temperature in Celsius:";
      cin >> k;
    }

  // CToF() function to convert the temperature
  double j1() {
    // initialising float type variables to
    // perform operations
    float h;

    h = ((k* 9) / 5) + 32;

    // returning converted temperature
    return h;
  }
};

int main() {
  // create a object
  temperature C;

  // float type variable to
  // store converted temperature
  float h;

  // function is called by the object to
  // store the temperature
  C.jaman();

  // CToF() function to convert the temperature
  h= C.j1();

  cout << "Temperature in Fahrenheit :" << h;

  return 0;
}
