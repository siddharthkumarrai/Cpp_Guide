# C++ Guide

- #include -> Preprocessor directives
- using full namespace
```cpp
#include <iostream>

using namespace std;

int main () {
  cout << "siddharth";
}
```
- using namespace methods
```cpp
#include <iostream>

int main () {
  std::cout << "siddharth" << std::endl;
}
```
- namespace way to use
```cpp
#include <iostream>

using std::cout;
using std::endl;

int main () {
  std::cout << "siddharth" << std::endl;
}
```
