## 1. C++ Language Basics

* Syntax
* `main`
* Variables
* Data types
* `std::cout`
* `std::cin`
* `int`
* `double`
* `char`
* `bool`
* `std::string`
* `\n`
* `return 0`
* `#include <iostream>`
* `#include <string>`
* `using namespace std`
* Assignment operators
* Arithmetic operators
* Comparison operators
* Logical operators
* Integer division
* Remainder operator `%`
* `++`
* `--`
* `+=`
* `-=`
* `*=`
* `/=`



## 2. Control Flow

* `if`
* `else`
* `else if`
* `switch`
* `case`
* `break`
* `default`
* `&&` / AND
* `||` / OR
* `!` / NOT
* `while`
* `do while`
* `for`
* Infinite loops
* `range-based for`
* Choosing between `if` and `switch`
* Choosing between `while` and `for`
* Using `%` to detect even numbers

 

## 3. Functions and Scope

* Function definition
* Function call
* `void`
* Return types
* Parameters
* Arguments
* `return`
* Scope
* Nested scopes
* Function scope
* Shadowing
* Pass by Value
* `const`
* Reference parameters



## 4. References, Pointers and Memory

* Reference
* Pointer
* `int&`
* `int*`
* Address of a variable
* Dereferencing
* `new`
* `delete`
* `delete[]`
* Stack
* Heap
* Pointer vs Reference
* Pointer and Array relationship
* Array
* Array of `struct`
* Object lifetime



## 5. Strings, Arrays and `size_t`

* `std::string`
* String indexing
* String size
* `size_t`
* Array indexing
* Array traversal
* Range-based `for`
* String and Array relationship

## 6. Structures and Containers

* `struct`
* `std::vector`
* `std::array`
* `std::map`
* `std::set`
* `std::unordered_map`
* `std::unordered_set`
* `std::pair`
* `std::tuple`
* Iterators
* `begin()`
* `end()`
* `cbegin()`
* `cend()`
* `const_iterator`
* Vector operations
* Passing `vector` to functions
* `size`
* `capacity`



## 7. STL Algorithms and Ranges

* `std::sort`
* `std::find`
* `std::find_if`
* `std::count_if`
* `std::any_of`
* `std::all_of`
* `std::none_of`
* `std::min_element`
* `std::max_element`
* `std::transform`
* `std::remove`
* `std::remove_if`
* `std::ranges::sort`
* `std::ranges::find`
* `std::ranges::find_if`
* `std::ranges::remove_if`
* `std::views::filter`
* `std::views::transform`
* `std::views::reverse`
* `std::views::take`
* `std::ranges::to`
* `erase-remove idiom`
* `std::erase`



## 8. Lambda

* Lambda expressions
* Lambda capture
* Capture by value
* Capture by reference
* `[minimumAge]`
* `[&minimumAge]`
* Lambda with algorithms
* Lambda with ranges



## 9. OOP

* `class`
* `struct`
* Object
* `private`
* `public`
* `protected`
* Constructor
* Destructor
* Object lifetime
* `this`
* `const` member functions
* Encapsulation
* Interface design
* Inheritance
* Polymorphism
* `virtual`
* `override`
* Pure virtual function
* Abstract class
* Composition
* HAS-A relationship
* Construction order
* Destruction order
* Combining Inheritance and Composition



## 10. Modern C++

* `auto`
* Type Deduction
* `nullptr`
* `constexpr`
* `consteval`
* `static_assert`
* `if constexpr`
* `std::optional`
* `std::variant`
* `std::visit`
* `std::string_view`
* `std::span`
* C++20 ranges



## 11. Smart Pointers and RAII

* `std::unique_ptr`
* `std::shared_ptr`
* `std::weak_ptr`
* `std::make_unique`
* `std::make_shared`
* `use_count()`
* `lock()`
* Ownership
* Unique ownership
* Shared ownership
* Non-owning reference
* Circular Reference
* Control Block
* Reference Counting
* RAII
* Lifetime management
* `std::move` with ownership

 

## 12. Move Semantics and Value Categories

* Copy Constructor
* Move Constructor
* Move Assignment
* Move Semantics
* Rvalue Reference
* `std::move`
* lvalue
* prvalue
* xvalue
* glvalue
* rvalue
* Reference Binding
* Overload Resolution
* Reference Collapsing
* Forwarding Reference
* `std::forward`
* Perfect Forwarding
* Variadic Perfect Forwarding



## 13. Rule of 3 / 5 / 0

* Rule of 3
* Rule of 5
* Rule of 0
* Copy operations
* Move operations
* Resource ownership
* Relationship between special member functions and resource management

## 14. Exceptions and Error Handling

* Exception
* `try`
* `catch`
* `throw`
* `noexcept`
* `assert`
* Undefined Behavior
* Memory errors
* Warnings



## 15. Templates and Concepts

* Function Templates
* Class Templates
* Template Argument Deduction
* Template Specialization
* Partial Specialization
* Variadic Templates
* Fold Expressions
* Concepts
* `if constexpr`
* Perfect Forwarding with Templates



## 16. Concurrency

* `std::thread`
* `std::mutex`
* `std::lock_guard`
* `std::unique_lock`
* `std::condition_variable`
* `std::condition_variable_any`
* `std::atomic`
* `std::async`
* `std::future`
* `std::promise`
* `std::packaged_task`
* `std::jthread`
* `std::stop_token`
* `std::stop_callback`
* Thread-safe Queue



## 17. CMake and Build System

* CMake
* `CMakeLists.txt`
* Multi-file projects
* `include/`
* `src/`
* Target
* `add_library`
* `add_executable`
* `target_link_libraries`
* `PRIVATE`
* `PUBLIC`
* `INTERFACE`
* Static Library
* Shared Library
* Library structure
* Separating Library from Executable
* Precompiled Headers / PCH
* `target_precompile_headers`
* Compiler warnings
* `-Wall`
* `-Wextra`
* `-Wpedantic`
* Debug / Release
* `CMAKE_BUILD_TYPE`
* Generator Expressions
* Single-config generators
* Multi-config generators
* `CMakePresets.json`
* Toolchain

 

## 18. C++ Modules and Library Architecture

* C++ Modules
* Module Interface
* `export module`
* `import`
* Module Partitions
* `export import`
* Public API
* Internal Implementation
* Public Headers
* API separation
* Library architecture
* Target dependencies
* `install()`
* Build Tree
* Install Tree
* Exporting Targets
* `find_package`
* Config packages
* `Config.cmake`
* `Targets.cmake`
* Library installation
* Library packaging
* Versioning

 

## 19. Dependency Management

* Dependency Management
* `vcpkg`
* CMake integration
* Package Management
* `find_package`
* CMake Presets
* Toolchain files

## 20. Debugging and Sanitizers

* Debug Symbols
* GDB
* Breakpoint
* Step Over
* Step Into
* Watch
* Call Stack
* Debug Configuration
* AddressSanitizer
* UndefinedBehaviorSanitizer
* ThreadSanitizer
* Heap Buffer Overflow
* Stack Buffer Overflow
* Heap Use After Free
* Memory Error Location
* Stack Trace
* Sanitizer configurations

 

## 21. Performance and Memory

* Object Layout
* `sizeof`
* `alignof`
* Padding
* Alignment
* Cache
* Cache Locality
* Array of Structures / AoS
* Structure of Arrays / SoA
* Cache Line
* False Sharing
* Branch Prediction
* Branch Misprediction
* Memory Allocation
* `new` / `delete` cost
* Vector Reallocation
* `size`
* `capacity`
* Contiguous Storage
* Pointer Invalidation
* Reference Invalidation
* Iterator Invalidation
* Small String Optimization / SSO
* Small Object Optimization / SBO

  

## 22. Design Patterns

* Strategy Pattern
* Factory Pattern
* Dependency Injection
* Adapter Pattern
* Facade Pattern
* Decorator Pattern
* Observer Pattern
* Command Pattern
* Undo / Redo
* Undo Stack
* Choosing a Pattern based on the problem
* Avoiding Overengineering

 

## 23. SOLID

* Single Responsibility Principle / SRP
* Open/Closed Principle / OCP
* Liskov Substitution Principle / LSP
* Interface Segregation Principle / ISP
* Dependency Inversion Principle / DIP
* Abstraction
* Dependency Injection in relation to SOLID

## 24. Software Architecture

* Composition
* Dependency Direction
* Coupling
* Cohesion
* Interface Design
* Dependency Injection
* Dependency Inversion
* Public API vs Internal Implementation
* Overengineering
* Combining Design Patterns
* Architecture based on the problem



## Overall C++ Path Covered

* C++ Basics
* Memory / Pointer / Reference
* STL and Algorithms
* OOP
* Modern C++
* Templates and Concepts
* RAII and Memory Management
* Concurrency
* Debugging and Sanitizers
* Modules + Professional CMake
* Library / Package / Install / `find_package`
* Dependency Management / `vcpkg`
* Value Categories / Move / Forwarding
* Performance and Advanced Memory
* Design Patterns
* Architecture

