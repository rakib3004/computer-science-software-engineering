# 1. What is the correct syntax to declare a variable in C?

A) var x = 10;
B) int x = 10;
C) x = 10;
D) integer x = 10;
**Answer** : B) int x = 10;
**Explanation** : In C, variables must be declared with a data type (e.g., int for integers) before
use. Option B is the correct syntax.

# 2. Which of the following is a valid identifier in C?

A) 2variable
B) _variable
C) variable-name
D) $variable
**Answer** : B) _variable
**Explanation** : Identifiers in C must start with a letter or underscore and can include letters, digits,
or underscores. Option B is valid, while A starts with a digit, C includes a hyphen, and D uses
an invalid character ($).

# 3. What is the size of an int data type in C on a 32-bit system?

A) 2 bytes
B) 4 bytes
C) 8 bytes


D) Depends on the compiler
**Answer** : B) 4 bytes
**Explanation** : On a 32-bit system, an int typically occupies 4 bytes, though it can vary slightly
depending on the compiler or system architecture.

# 4. What does the break statement do in a loop?

A) Terminates the program
B) Exits the current loop iteration
C) Skips the current iteration and continues with the next
D) Exits the entire loop
**Answer** : D) Exits the entire loop
**Explanation** : The break statement terminates the loop entirely, transferring control to the
statement following the loop.

# 5. Which operator is used to access the address of a variable in C?

A) *

B) &

C) %

D) #

**Answer** : B) &
**Explanation** : The & operator returns the memory address of a variable, used in pointer
operations.


# 6. What is the output of the following code?

c
#include <stdio.h>
int main() {
printf("%d", 5 / 2 );
return 0 ;
}
A) 2.
B) 2
C) 3
D) 0
**Answer** : B) 2
**Explanation** : In C, division between two integers (5 / 2) performs integer division, discarding the
decimal part, resulting in 2.

# 7. Which of the following is the correct way to declare a function in C?

A) function myFunc() {}
B) void myFunc() {}
C) myFunc() {}
D) int myFunc {}
**Answer** : B) void myFunc() {}
**Explanation** : Functions in C must specify a return type (e.g., void for no return value) and follow
the syntax return_type function_name(parameters).


# 8. What is the purpose of the return 0 statement in the main function?

A) Terminates the loop
B) Indicates successful program execution
C) Returns a null pointer
D) Resets the program
**Answer** : B) Indicates successful program execution
**Explanation** : In the main function, return 0 signals to the operating system that the program
executed successfully.

# 9. Which loop in C guarantees at least one execution of the loop body?

A) for
B) while
C) do-while
D) None of the above
**Answer** : C) do-while
**Explanation** : The do-while loop executes the loop body at least once before checking the
condition.

# 10. What is the correct way to declare a pointer in C?

A) int _ptr;
B) int ptr_ ;
C) *int ptr;


D) pointer int ptr;
**Answer** : A) int *ptr;
**Explanation** : A pointer is declared using the * symbol after the data type, as in int *ptr;.

# 11. What will be the output of the following code?

c
#include <stdio.h>
int main() {
int x = 10 ;
if (x = 5 ) {
printf("True");
} else {
printf("False");
}
return 0 ;
}
A) True
B) False
C) Compilation error
D) Runtime error
**Answer** : A) True


**Explanation** : The if (x = 5) uses an assignment operator (=), not a comparison (==). It assigns 5
to x, which evaluates to a non-zero value (true), so "True" is printed.

# 12. Which of the following is used to include a header file in C?

A) #include <stdio.h>
B) include <stdio.h>
C) #import <stdio.h>
D) import <stdio.h>
**Answer** : A) #include <stdio.h>
**Explanation** : The #include directive is used to include header files in C, with the syntax
#include <filename> for standard libraries.

# 13. What is the purpose of the const keyword in C?

A) To define a variable that cannot be modified
B) To declare a constant function
C) To allocate memory dynamically
D) To initialize a loop
**Answer** : A) To define a variable that cannot be modified
**Explanation** : The const keyword declares a variable whose value cannot be changed after
initialization.

# 14. What will be the output of the following code?

c
#include <stdio.h>


int main() {
int a = 5 , b = 10 ;
printf("%d", a + b++);
return 0 ;
}
A) 15
B) 16
C) 14
D) 10
**Answer** : A) 15
**Explanation** : The b++ is a post-increment, so b is used as 10 in the expression a + b++ (5 + 10
= 15), and b is incremented afterward.

# 15. Which of the following is not a valid storage class in C?

A) auto
B) static
C) extern
D) global
**Answer** : D) global
**Explanation** : C has four storage classes: auto, static, extern, and register. global is not a
storage class.


# 16. What is the purpose of the sizeof operator in C?

A) To return the size of a variable or data type in bytes
B) To allocate memory
C) To compare two variables
D) To initialize a variable
**Answer** : A) To return the size of a variable or data type in bytes
**Explanation** : The sizeof operator returns the size (in bytes) of a variable or data type.

# 17. What will be the output of the following code?

c
#include <stdio.h>
int main() {
int arr[ 3 ] = { 1 , 2 , 3 };
printf("%d", arr[ 3 ]);
return 0 ;
}
A) 3
B) 0
C) Undefined behavior
D) Compilation error
**Answer** : C) Undefined behavior


**Explanation** : Accessing arr[3] is out of bounds for an array of size 3 (valid indices are 0 to 2),
leading to undefined behavior.

# 18. Which of the following is used to dynamically allocate memory in C?

A) malloc()
B) new()
C) alloc()
D) create()
**Answer** : A) malloc()
**Explanation** : The malloc() function is used to dynamically allocate memory in C.

# 19. What is the correct way to pass an array to a function in C?

A) void myFunc(int arr)
B) void myFunc(int arr[])
C) void myFunc(int *arr[])
D) void myFunc(int &arr)
**Answer** : B) void myFunc(int arr[])
**Explanation** : Arrays in C are passed as pointers, and the syntax int arr[] is commonly used to
indicate an array parameter.

# 20. What does the continue statement do in a loop?

A) Exits the loop entirely
B) Skips the current iteration and proceeds to the next


C) Terminates the program
D) Restarts the loop
**Answer** : B) Skips the current iteration and proceeds to the next
**Explanation** : The continue statement skips the rest of the current loop iteration and moves to
the next iteration.

# 21. What is the output of the following code?

c
#include <stdio.h>
int main() {
int x = 10 ;
printf("%d", x++ + ++x);
return 0 ;
}
A) 20
B) 21
C) 22
D) Undefined behavior
**Answer** : D) Undefined behavior
**Explanation** : The expression x++ + ++x modifies x multiple times without a sequence point,
leading to undefined behavior.

# 22. Which of the following is a correct way to define a constant in C?


A) #define PI 3.
B) const PI = 3.14;
C) #const PI 3.
D) define PI = 3.14;
**Answer** : A) #define PI 3.
**Explanation** : The #define directive is used to define constants in C. const variables are another
way but require a data type (e.g., const float PI = 3.14;).

# 23. What is the purpose of the void pointer in C?

A) Points to a variable of any data type
B) Points to no memory location
C) Declares a null pointer
D) Allocates memory dynamically
**Answer** : A) Points to a variable of any data type
**Explanation** : A void pointer is a generic pointer that can point to any data type but cannot be
dereferenced directly.

# 24. What will be the output of the following code?

c
#include <stdio.h>
int main() {
int x = 5 ;
switch (x) {


case 5 : printf("Five ");
default: printf("Default");
}
return 0 ;
}
A) Five
B) Default
C) Five Default
D) Compilation error
**Answer** : C) Five Default
**Explanation** : The switch statement executes the matching case (5), printing "Five ". Without a
break, it falls through to the default case, printing "Default".

# 25. Which of the following is used to free dynamically allocated memory in

# C?

A) free()
B) delete()
C) release()
D) dealloc()
**Answer** : A) free()
**Explanation** : The free() function is used to deallocate memory previously allocated by malloc(),
calloc(), or realloc().


