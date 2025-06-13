# C++ Guide

```mermaid
graph TD
    A["C++"] --> B["Platform dependent"]
    A --> C["Object-oriented"]
    B --> D["Statically-typed"]
    C --> E["Speed"]
    D --> F["Pointers"]
    
    style A fill:#f9f9f9,stroke:#333,stroke-width:3px,color:#000
    style B fill:#e1f5fe,stroke:#0277bd,stroke-width:2px,color:#000
    style C fill:#e1f5fe,stroke:#0277bd,stroke-width:2px,color:#000
    style D fill:#fff3e0,stroke:#ef6c00,stroke-width:2px,color:#000
    style E fill:#fff3e0,stroke:#ef6c00,stroke-width:2px,color:#000
    style F fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px,color:#000
```
- #include -> Preprocessor directives
## How to use namespace
- Method 1
```cpp
#include <iostream>

using namespace std;

int main () {
  cout << "siddharth";
}
```
- Method 2
```cpp
#include <iostream>

int main () {
  std::cout << "siddharth" << std::endl;
}
```
- Method 3
```cpp
#include <iostream>

using std::cout;
using std::endl;

int main () {
  std::cout << "siddharth" << std::endl;
}
```
### Variable
```cpp
const int uuid = 756984;

uuid = 44587; // error; ❌
```
