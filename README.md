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
### Key Features Explained

- Platform dependent: C++ code needs to be compiled for specific platforms/architectures
- Object-oriented: Supports classes, objects, inheritance, polymorphism, and encapsulation
- Statically-typed: Variable types are checked at compile time
- Speed: Compiled language that produces efficient machine code
- Pointers: Direct memory access and manipulation capabilities
## #include -> Preprocessor directives
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
## C++ Data Types
##### This diagram shows the classification of data types in C++.

```mermaid
graph TD
    A["Data types"] --> B["primitive"]
    A --> C["Derived"]
    A --> D["user-defined"]
    
    B --> E["int<br/>float<br/>double<br/>char<br/>boolean<br/>void"]
    C --> F["Array<br/>function<br/>pointer<br/>reference"]
    D --> G["Structure<br/>Union<br/>Enum<br/>Class<br/>Typedef<br/>String"]
    
    style A fill:#e1f5fe,stroke:#0277bd,stroke-width:3px,color:#000
    style B fill:#f3e5f5,stroke:#333,stroke-width:2px,color:#000
    style C fill:#e1f5fe,stroke:#0277bd,stroke-width:2px,color:#000
    style D fill:#f3e5f5,stroke:#333,stroke-width:2px,color:#000
    style E fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px,color:#000
    style F fill:#fff3e0,stroke:#ef6c00,stroke-width:2px,color:#000
    style G fill:#fff3e0,stroke:#ef6c00,stroke-width:2px,color:#000
```
