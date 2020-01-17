# -this-Pointer-in-cpp
this’ pointer, it is important to know how objects look at functions and data members of a class.
Each object gets its own copy of the data member.
All-access the same function definition as present in the code segment.
The compiler supplies an implicit pointer along with the names of the functions as ‘this’.
The ‘this’ pointer is passed as a hidden argument to all nonstatic member function calls and is available as a local variable within the body of all nonstatic functions.
 ‘this’ pointer is not available in static member functions as static member functions can be called without any object (with class name).
For a class X, the type of this pointer is ‘X* ‘. Also, if a member function of X is declared as const, then the type of this pointer is ‘const X *’

