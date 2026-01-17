#c-language #programming #cheatsheet #computer-science

1. [[#1. Foundations|1. Foundations]]
	1. [[#1. Foundations#1.1. Your First Program: "Hello, World!"|1.1. Your First Program: "Hello, World!"]]
	2. [[#1. Foundations#1.2. Basic Data Types|1.2. Basic Data Types]]
	3. [[#1. Foundations#1.3. Variables and Constants|1.3. Variables and Constants]]
	4. [[#1. Foundations#1.4. Operators|1.4. Operators]]
		1. [[#1.4. Operators#Arithmetic Operators|Arithmetic Operators]]
		2. [[#1.4. Operators#Relational & Logical Operators|Relational & Logical Operators]]
2. [[#2. Control Flow|2. Control Flow]]
	1. [[#2. Control Flow#2.1. Selective (Conditional) Structures|2.1. Selective (Conditional) Structures]]
		1. [[#2.1. Selective (Conditional) Structures#`if-else if-else`|`if-else if-else`]]
		2. [[#2.1. Selective (Conditional) Structures#`switch`|`switch`]]
	2. [[#2. Control Flow#2.2. Iterative (Looping) Structures|2.2. Iterative (Looping) Structures]]
		1. [[#2.2. Iterative (Looping) Structures#`for` loop|`for` loop]]
		2. [[#2.2. Iterative (Looping) Structures#`while` loop|`while` loop]]
		3. [[#2.2. Iterative (Looping) Structures#`do-while` loop|`do-while` loop]]
3. [[#3. Functions|3. Functions]]
	1. [[#3. Functions#3.1. Function Parameters: Pass-by-Value|3.1. Function Parameters: Pass-by-Value]]
	2. [[#3. Functions#3.2. Function Parameters: Simulating Pass-by-Reference|3.2. Function Parameters: Simulating Pass-by-Reference]]
		1. [[#3.2. Function Parameters: Simulating Pass-by-Reference#Example: The `swap` Function|Example: The `swap` Function]]
		2. [[#3.2. Function Parameters: Simulating Pass-by-Reference#How It Works:|How It Works:]]
4. [[#4. Arrays and Strings|4. Arrays and Strings]]
	1. [[#4. Arrays and Strings#4.1. Arrays|4.1. Arrays]]
	2. [[#4. Arrays and Strings#4.2. Strings|4.2. Strings]]
5. [[#5. Pointers (The Core of Advanced C)|5. Pointers (The Core of Advanced C)]]
	1. [[#5. Pointers (The Core of Advanced C)#5.1. Declaring and Using Pointers|5.1. Declaring and Using Pointers]]
	2. [[#5. Pointers (The Core of Advanced C)#5.2. Pointers and Arrays|5.2. Pointers and Arrays]]
	3. [[#5. Pointers (The Core of Advanced C)#5.3. Pointers and Functions (Simulating Pass-by-Reference)|5.3. Pointers and Functions (Simulating Pass-by-Reference)]]
6. [[#6. Structs|6. Structs]]
	1. [[#6. Structs#6.1. Declaring and Using Structs|6.1. Declaring and Using Structs]]
	2. [[#6. Structs#6.2. Pointers to Structs and the `->` Operator|6.2. Pointers to Structs and the `->` Operator]]
7. [[#7. Dynamic Memory Allocation|7. Dynamic Memory Allocation]]
	1. [[#7. Dynamic Memory Allocation#7.1. `malloc` and `free`|7.1. `malloc` and `free`]]
8. [[#8. Advanced Data Structures: Linked Lists|8. Advanced Data Structures: Linked Lists]]
	1. [[#8. Advanced Data Structures: Linked Lists#8.1. Creating and Manipulating a Simple Linked List|8.1. Creating and Manipulating a Simple Linked List]]
9. [[#9. File I/O (Input/Output)|9. File I/O (Input/Output)]]
	1. [[#9. File I/O (Input/Output)#9.1. Opening, Reading, and Writing Files|9.1. Opening, Reading, and Writing Files]]
10. [[#10. Advanced Pointer Concepts|10. Advanced Pointer Concepts]]
	1. [[#10. Advanced Pointer Concepts#10.1. Pointers to Pointers (`**`)|10.1. Pointers to Pointers (`**`)]]
	2. [[#10. Advanced Pointer Concepts#10.2. `const` and Pointers|10.2. `const` and Pointers]]
11. [[#11. Recursion|11. Recursion]]
12. [[#12. The C Preprocessor|12. The C Preprocessor]]
	1. [[#12. The C Preprocessor#12.1. Macro Functions|12.1. Macro Functions]]
	2. [[#12. The C Preprocessor#12.2. Conditional Compilation|12.2. Conditional Compilation]]
13. [[#13. Bitwise Operators|13. Bitwise Operators]]
14. [[#14. Type Definitions (`typedef`) and Enumerations (`enum`)|14. Type Definitions (`typedef`) and Enumerations (`enum`)]]
	1. [[#14. Type Definitions (`typedef`) and Enumerations (`enum`)#14.1. `typedef`|14.1. `typedef`]]
	2. [[#14. Type Definitions (`typedef`) and Enumerations (`enum`)#14.2. `enum`|14.2. `enum`]]
15. [[#15. Function Pointers|15. Function Pointers]]
16. [[#16. The C Standard Library (A Deeper Look)|16. The C Standard Library (A Deeper Look)]]
	1. [[#16. The C Standard Library (A Deeper Look)#16.1. `<stdlib.h>` - General Utilities|16.1. `<stdlib.h>` - General Utilities]]
	2. [[#16. The C Standard Library (A Deeper Look)#16.2. `<math.h>` - Mathematics|16.2. `<math.h>` - Mathematics]]
17. [[#17. Command-Line Arguments|17. Command-Line Arguments]]
18. [[#18. Advanced Error Handling|18. Advanced Error Handling]]
19. [[#19. Unions (`union`)|19. Unions (`union`)]]
20. [[#20. Multi-File Projects and Header Guards|20. Multi-File Projects and Header Guards]]
	1. [[#20. Multi-File Projects and Header Guards#Example: A Simple Math Utilities Module|Example: A Simple Math Utilities Module]]
21. [[#21. Advanced String Manipulation|21. Advanced String Manipulation]]
22. [[#22. Advanced Dynamic Memory Allocation|22. Advanced Dynamic Memory Allocation]]
23. [[#23. The `static` Keyword|23. The `static` Keyword]]
	1. [[#23. The `static` Keyword#23.1. Static Local Variables|23.1. Static Local Variables]]
	2. [[#23. The `static` Keyword#23.2. Static Global Variables and Functions|23.2. Static Global Variables and Functions]]
24. [[#24. The `volatile` Keyword|24. The `volatile` Keyword]]
25. [[#25. Variable Scoping and Storage Duration|25. Variable Scoping and Storage Duration]]
	1. [[#25. Variable Scoping and Storage Duration#25.1. Scope|25.1. Scope]]
	2. [[#25. Variable Scoping and Storage Duration#25.2. Storage Duration & Specifiers|25.2. Storage Duration & Specifiers]]
26. [[#26. Number Systems: Binary and Hexadecimal|26. Number Systems: Binary and Hexadecimal]]
	1. [[#26. Number Systems: Binary and Hexadecimal#26.1. Binary (Base 2)|26.1. Binary (Base 2)]]
	2. [[#26. Number Systems: Binary and Hexadecimal#26.2. Hexadecimal (Base 16)|26.2. Hexadecimal (Base 16)]]
	3. [[#26. Number Systems: Binary and Hexadecimal#26.3. Using Hex and Binary Literals in C|26.3. Using Hex and Binary Literals in C]]
27. [[#27. Common Pitfalls and Best Practices|27. Common Pitfalls and Best Practices]]
	1. [[#27. Common Pitfalls and Best Practices#27.1. Buffer Overflows|27.1. Buffer Overflows]]
	2. [[#27. Common Pitfalls and Best Practices#27.2. Memory Leaks|27.2. Memory Leaks]]
	3. [[#27. Common Pitfalls and Best Practices#27.3. Dangling Pointers|27.3. Dangling Pointers]]
	4. [[#27. Common Pitfalls and Best Practices#27.4. Off-by-One Errors|27.4. Off-by-One Errors]]

## 1. Foundations

### 1.1. Your First Program: "Hello, World!"

Every C journey starts here. This program demonstrates the basic structure, including the `main` function, header inclusion, and a function call to print output.

```c
// #include is a preprocessor directive that tells the compiler to include
// the contents of the standard input/output library file.
#include <stdio.h>

// The main function is the entry point of every C program.
// 'int' means it will return an integer value to the operating system.
int main() {
    // printf is a function from stdio.h used to print formatted output to the console.
    // "\n" is a newline character, moving the cursor to the next line.
    printf("Hello, World!\n");

    // Returning 0 indicates that the program executed successfully.
    return 0;
}
```

### 1.2. Basic Data Types

C is a statically-typed language, meaning you must declare the type of every variable.

> [!note] Signed vs. Unsigned
> By default, integer types (`int`, `short`, `long`) are **signed**, meaning they can hold both positive and negative numbers. Prepend `unsigned` to make them only hold non-negative numbers, effectively doubling the positive range.

| Type | Description | Example | Format Specifier (`printf`) |
|---|---|---|---|
| `int` | Integer (whole number) | `int age = 30;` | `%d` |
| `char` | Single character (stored as a number) | `char initial = 'J';` | `%c` |
| `float` | Single-precision floating-point number | `float temp = 98.6f;` | `%f` |
| `double` | Double-precision floating-point number | `float pi = 3.14159;` | `%lf` |
| `void` | Represents "no type" | `void myFunction();` | N/A |
| `unsigned int` | Non-negative integer | `unsigned int count = 100;` | `%u` |

```c
#include <stdio.h>

int main() {
    int students = 150;
    double average_gpa = 3.45;
    char grade = 'A';
    unsigned int error_code = 404;

    printf("Number of students: %d\n", students);
    printf("Average GPA: %.2lf\n", average_gpa); // .2lf limits to 2 decimal places
    printf("Top grade: %c\n", grade);
    printf("HTTP Error: %u\n", error_code);

    return 0;
}
```

### 1.3. Variables and Constants

- **Variables**: Named storage locations whose values can be changed.
- **Constants**: Named storage locations whose values cannot be changed after initialization.

```c
#include <stdio.h>

// Define a constant using a preprocessor macro (traditional C way)
#define PI 3.14159

int main() {
    int radius = 10;
    // Use the 'const' keyword to create a constant variable (modern C way)
    const double GRAVITY = 9.81;

    // You can change a variable
    radius = 20;

    // You CANNOT change a constant. This would cause a compiler error:
    // GRAVITY = 10.0; // ERROR!

    printf("Radius: %d\n", radius);
    printf("Value of PI: %f\n", PI);
    printf("Gravity: %lf\n", GRAVITY);

    return 0;
}
```

### 1.4. Operators

#### Arithmetic Operators
`+` (addition), `-` (subtraction), `*` (multiplication), `/` (division), `%` (modulo/remainder).

```c
int a = 10, b = 4;
int sum = a + b;      // 14
int diff = a - b;     // 6
int prod = a * b;     // 40
int quot = a / b;     // 2 (integer division)
int rem = a % b;      // 2
```

#### Relational & Logical Operators
Used in conditions. Relational operators (`==`, `!=`, `>`, `<`, `>=`, `<=`) compare two values. Logical operators (`&&` for AND, `||` for OR, `!` for NOT) combine conditions.

```c
int x = 5;
int y = 10;

// Relational
(x == y)   // false (0)
(x != y)   // true (1)
(x < y)    // true (1)

// Logical
(x < 10 && y > 5) // true (1) because both conditions are true
(x > 10 || y < 5) // false (0) because both conditions are false
!(x == y)         // true (1) because (x == y) is false
```

## 2. Control Flow

### 2.1. Selective (Conditional) Structures

These structures allow the program to execute different blocks of code based on a condition.

#### `if-else if-else`
```c
#include <stdio.h>

int main() {
    int score = 85;

    if (score >= 90) {
        printf("Grade: A\n");
    } else if (score >= 80) {
        printf("Grade: B\n"); // This block will execute
    } else if (score >= 70) {
        printf("Grade: C\n");
    } else {
        printf("Grade: F\n");
    }
    return 0;
}
```

#### `switch`
A `switch` statement is a cleaner way to compare a single variable against multiple constant values.

```c
#include <stdio.h>

int main() {
    char operator = '+';
    int a = 10, b = 5;

    switch (operator) {
        case '+':
            printf("Result: %d\n", a + b);
            break; // 'break' exits the switch block
        case '-':
            printf("Result: %d\n", a - b);
            break;
        case '*':
            printf("Result: %d\n", a * b);
            break;
        default:
            // 'default' runs if no case matches
            printf("Invalid operator\n");
    }
    return 0;
}
```

### 2.2. Iterative (Looping) Structures

Loops execute a block of code repeatedly.

#### `for` loop
Ideal when you know exactly how many times you want to loop.

```c
#include <stdio.h>

int main() {
    // Loop initialization; condition; increment/decrement
    for (int i = 0; i < 5; i++) {
        printf("for loop iteration: %d\n", i);
    }
    return 0;
}
```

#### `while` loop
Ideal when you want to loop as long as a condition is true, and you don't know the number of iterations beforehand.

```c
#include <stdio.h>

int main() {
    int count = 0;
    while (count < 5) {
        printf("while loop iteration: %d\n", count);
        count++; // IMPORTANT: Update the condition variable!
    }
    return 0;
}
```

#### `do-while` loop
Similar to `while`, but the condition is checked *after* the loop body executes. This guarantees the loop runs at least once.

```c
#include <stdio.h>

int main() {
    int count = 0;
    do {
        printf("do-while loop iteration: %d\n", count);
        count++;
    } while (count < 5);
    return 0;
}
```

## 3. Functions

Functions are reusable blocks of code that perform a specific task.

### 3.1. Function Parameters: Pass-by-Value

In C, arguments are passed to functions **by value**. This means the function receives a *copy* of the argument's value, not the original variable itself. Changing the parameter inside the function does **not** affect the original variable.

```c
#include <stdio.h>

// This function takes an integer 'x' by value.
void tryToChange(int x) {
    x = 100; // This only changes the local copy 'x'
    printf("Inside function, x = %d\n", x);
}

int main() {
    int num = 5;
    printf("Before function call, num = %d\n", num);

    tryToChange(num); // Pass the value of 'num' (which is 5)

    printf("After function call, num = %d\n", num); // 'num' is still 5
    return 0;
}
```
> [!important]
> To modify a variable from inside a function, you must pass a **pointer** to that variable. See section [[#5.4. Pointers and Functions]].

### 3.2. Function Parameters: Simulating Pass-by-Reference

While C technically only supports **pass-by-value**, you can simulate **pass-by-reference** by passing pointers to variables. Instead of passing a copy of the variable's value, you pass a copy of its memory address. The function can then use this address to access and modify the original variable in the calling function's scope.

This is the primary way to write functions that need to modify more than one piece of data or return complex data structures.

#### Example: The `swap` Function

The classic example is a function that swaps the values of two integers. This is impossible with pass-by-value alone.

```c
#include <stdio.h>

// This function takes two POINTERS to integers as parameters.
// It's designed to swap the values of the variables these pointers point to.
void swap(int *num1_ptr, int *num2_ptr) {
    int temp;

    // 1. Store the value at the first address in a temporary variable
    temp = *num1_ptr; // *num1_ptr dereferences the pointer to get the value of 'a'

    // 2. Overwrite the value at the first address with the value from the second address
    *num1_ptr = *num2_ptr; // The value of 'a' is now the value of 'b'

    // 3. Overwrite the value at the second address with the saved temporary value
    *num2_ptr = temp; // The value of 'b' is now the original value of 'a'

    printf("Inside swap function: a = %d, b = %d\n", *num1_ptr, *num2_ptr);
}

int main() {
    int a = 10;
    int b = 20;

    printf("Before swap function: a = %d, b = %d\n", a, b);

    // To simulate pass-by-reference, we pass the ADDRESSES of 'a' and 'b'
    swap(&a, &b);

    // The original variables 'a' and 'b' have been modified
    printf("After swap function:  a = %d, b = %d\n", a, b);

    return 0;
}
```

#### How It Works:

1.  **Function Signature**: `void swap(int *num1_ptr, int *num2_ptr)` tells the compiler that `swap` expects two pointers to integers, not the integers themselves.
2.  **The Call**: `swap(&a, &b);` uses the **address-of operator `&`** to pass the memory addresses of `a` and `b` to the function.
3.  **Inside the Function**: The parameters `num1_ptr` and `num2_ptr` now hold the addresses of `a` and `b`. By using the **dereference operator `*`** (e.g., `*num1_ptr`), the function can access and modify the actual data stored at those addresses.
4.  **Result**: Because the function operated directly on the memory locations of `a` and `b`, their values in `main` are permanently changed after the function call.

## 4. Arrays and Strings

### 4.1. Arrays

An array is a collection of elements of the same data type stored in contiguous memory locations.

```c
#include <stdio.h>

int main() {
    // Declaration and initialization
    int numbers[5] = {10, 20, 30, 40, 50};

    // Accessing elements using a zero-based index
    printf("First element: %d\n", numbers[0]); // 10
    printf("Third element: %d\n", numbers[2]); // 30

    // Modifying an element
    numbers[4] = 55;
    printf("Last element: %d\n", numbers[4]); // 55

    // Looping through an array
    for (int i = 0; i < 5; i++) {
        printf("Element at index %d: %d\n", i, numbers[i]);
    }
    return 0;
}
```

### 4.2. Strings

In C, a string is a null-terminated array of characters. The null character (`\0`) marks the end of the string.

```c
#include <stdio.h>
#include <string.h> // Required for string manipulation functions

int main() {
    // Two ways to declare a string
    char greeting1[] = "Hello"; // Compiler automatically adds '\0'
    char greeting2[6] = {'H', 'e', 'l', 'l', 'o', '\0'}; // Manual null terminator

    // Printing strings
    printf("Greeting 1: %s\n", greeting1);
    printf("Greeting 2: %s\n", greeting2);

    // Getting string length (does not count '\0')
    printf("Length of greeting1: %zu\n", strlen(greeting1));

    // Copying strings (be careful with buffer overflows!)
    char destination[20];
    strcpy(destination, greeting1); // Copies greeting1 into destination
    printf("Destination: %s\n", destination);

    return 0;
}
```

## 5. Pointers (The Core of Advanced C)

A pointer is a variable that stores the **memory address** of another variable.

### 5.1. Declaring and Using Pointers

- `*` (asterisk): Used to declare a pointer variable. Also used to **dereference** a pointer (access the value at the address it holds).
- `&` (ampersand): The "address-of" operator. It gets the memory address of a variable.

```c
#include <stdio.h>

int main() {
    int var = 10;
    // Declare a pointer 'ptr' that can hold the address of an integer
    int *ptr;

    // Store the address of 'var' in the pointer 'ptr'
    ptr = &var;

    printf("Value of var: %d\n", var);
    printf("Address of var: %p\n", (void*)&var); // %p is for pointers
    printf("Value of ptr (address of var): %p\n", (void*)ptr);
    // Dereference the pointer to get the value it points to
    printf("Value at address stored in ptr: %d\n", *ptr);

    // Changing the value using the pointer
    *ptr = 20;
    printf("New value of var: %d\n", var); // var is now 20!

    return 0;
}
```

### 5.2. Pointers and Arrays

The name of an array acts like a pointer to its first element.

```c
#include <stdio.h>

int main() {
    int arr[3] = {5, 10, 15};
    int *ptr = arr; // 'arr' decays to a pointer to its first element

    // Accessing elements with array notation
    printf("arr[1] = %d\n", arr[1]);

    // Accessing elements with pointer arithmetic
    printf("*(ptr + 1) = %d\n", *(ptr + 1)); // Same as arr[1]

    // Both point to the same memory location
    printf("Address of arr[1]: %p\n", (void*)&arr[1]);
    printf("Address of (ptr + 1): %p\n", (void*)(ptr + 1));

    return 0;
}
```

### 5.3. Pointers and Functions (Simulating Pass-by-Reference)

By passing a pointer to a function, you can modify the original variable from the caller's scope.

```c
#include <stdio.h>

// This function takes a POINTER to an integer
void actuallyChange(int *x_ptr) {
    // Dereference the pointer to change the value at that address
    *x_ptr = 100;
    printf("Inside function, value at address is now: %d\n", *x_ptr);
}

int main() {
    int num = 5;
    printf("Before function call, num = %d\n", num);

    // Pass the ADDRESS of 'num' to the function
    actuallyChange(&num);

    printf("After function call, num = %d\n", num); // 'num' is now 100!
    return 0;
}
```

## 6. Structs

A `struct` (structure) is a user-defined data type that groups together variables of different data types under a single name.

### 6.1. Declaring and Using Structs

```c
#include <stdio.h>
#include <string.h>

// 1. Define the 'struct' blueprint (often outside main)
struct Student {
    char name[50];
    int id;
    double gpa;
};

int main() {
    // 2. Declare a variable of the struct type
    struct Student student1;

    // 3. Access and assign values to members using the dot (.) operator
    strcpy(student1.name, "Alice Smith"); // Use strcpy for strings
    student1.id = 12345;
    student1.gpa = 3.8;

    // Print the member values
    printf("Student Name: %s\n", student1.name);
    printf("Student ID: %d\n", student1.id);
    printf("Student GPA: %.2lf\n", student1.gpa);

    return 0;
}
```

### 6.2. Pointers to Structs and the `->` Operator

When you have a pointer to a struct, you can access its members in two ways. The arrow `->` operator is a convenient shortcut.

```c
#include <stdio.h>
#include <string.h>

struct Student {
    char name[50];
    int id;
};

int main() {
    struct Student student1;
    strcpy(student1.name, "Bob Johnson");
    student1.id = 67890;

    // Create a pointer to the struct
    struct Student *student_ptr = &student1;

    // --- Accessing members via pointer ---

    // Method 1: Dereference the pointer, then use the dot operator.
    // Parentheses are required because '.' has higher precedence than '*'.
    printf("Student Name (Method 1): %s\n", (*student_ptr).name);

    // Method 2: Use the arrow '->' operator (preferred and cleaner)
    printf("Student ID (Method 2): %d\n", student_ptr->id);

    // You can also modify members using the arrow operator
    student_ptr->id = 54321;
    printf("New Student ID: %d\n", student1.id); // The original struct is changed

    return 0;
}
```

## 7. Dynamic Memory Allocation

Static variables (like global variables and arrays) have their memory allocated at compile time. Dynamic memory allocation allows you to request memory at **runtime** from the **heap**.

- **Heap**: A large pool of memory for dynamic allocation.
- **Stack**: Memory for local variables and function calls; managed automatically.

> [!warning] Memory Leaks
> Any memory you allocate dynamically **must be freed** using `free()`. Forgetting to do so causes a **memory leak**, where the program consumes more and more memory without releasing it.

In C, the stack and the heap are two fundamental regions of memory that manage your program's data, each with a different purpose and behavior. 

The **stack** is a highly organized and efficient region that handles local variables and the flow of function calls. Think of it like a stack of plates: when a function is called, a new "plate" containing its local variables is pushed onto the stack. When the function finishes, its plate is popped off, and all its variables are automatically destroyed. This automatic management makes the stack very fast, but it also means that memory on the stack is temporary and limited in size.

In contrast, the **heap** is a large, more flexible pool of memory used for dynamic allocation. While static and stack memory is handled for you, the heap allows you to explicitly request memory at runtime using functions like `malloc`. 

This is essential when you don't know how much memory you need until the program is running, or when you need data to outlive the function that created it. The trade-off for this flexibility is manual responsibility: you must explicitly return the memory to the heap using `free()` when you are finished with it. Forgetting to do so results in a **memory leak**, where the memory remains allocated but unusable for the rest of the program's execution.
### 7.1. `malloc` and `free`

- `malloc(size)`: Allocates `size` bytes of memory. Returns a `void*` pointer to the start of the block. Returns `NULL` if allocation fails.
- `free(ptr)`: Deallocates the memory block pointed to by `ptr`, making it available for future use.

```c
#include <stdio.h>
#include <stdlib.h> // Required for malloc and free

int main() {
    int n = 5;
    // Allocate memory for an array of 5 integers on the heap
    int *dynamic_array = (int*)malloc(n * sizeof(int));

    // ALWAYS check if malloc was successful
    if (dynamic_array == NULL) {
        printf("Memory allocation failed!\n");
        return 1; // Exit with an error code
    }

    // Use the dynamically allocated memory
    for (int i = 0; i < n; i++) {
        dynamic_array[i] = i * 10;
        printf("dynamic_array[%d] = %d\n", i, dynamic_array[i]);
    }

    // WHEN YOU ARE DONE, FREE THE MEMORY!
    // This is crucial to prevent memory leaks.
    free(dynamic_array);
    // It's good practice to set the pointer to NULL after freeing
    // to prevent using it accidentally (a "dangling pointer").
    dynamic_array = NULL;

    return 0;
}
```

> [!important] When to `free`
> You should `free` memory when you are certain you will no longer need it. A common pattern is to `free` memory in the same function or scope where it was allocated, or in the corresponding "cleanup" or "destructor" part of your program logic. For data structures like linked lists, you must free each node individually when you destroy the list.

## 8. Advanced Data Structures: Linked Lists

A linked list is a chain of **nodes**, where each node contains data and a pointer to the next node in the sequence. This is a perfect example of combining [[#6. Structs]], [[#5. Pointers (The Core of Advanced C)]], and [[#7. Dynamic Memory Allocation]].

### 8.1. Creating and Manipulating a Simple Linked List

```c
#include <stdio.h>
#include <stdlib.h>

// 1. Define the Node struct
struct Node {
    int data;
    struct Node* next; // Pointer to the next node of the same type
};

// Function to print the list
void printList(struct Node* head) {
    struct Node* current = head;
    printf("List: ");
    while (current != NULL) {
        printf("%d -> ", current->data);
        current = current->next; // Move to the next node
    }
    printf("NULL\n");
}

// Function to free the entire list
void freeList(struct Node* head) {
    struct Node* tmp;
    while (head != NULL) {
        tmp = head;       // Store current head
        head = head->next; // Move head to next node
        free(tmp);        // Free the old head
    }
    printf("List has been freed.\n");
}


int main() {
    // 2. Create nodes dynamically
    struct Node* head = NULL;
    struct Node* second = NULL;
    struct Node* third = NULL;

    head = (struct Node*)malloc(sizeof(struct Node));
    second = (struct Node*)malloc(sizeof(struct Node));
    third = (struct Node*)malloc(sizeof(struct Node));

    // 3. Link the nodes together
    head->data = 1;
    head->next = second;

    second->data = 2;
    second->next = third;

    third->data = 3;
    third->next = NULL; // The last node points to NULL

    // 4. Use the list
    printList(head);

    // 5. Free the entire list to prevent memory leaks
    freeList(head);
    // After freeList, head is now a dangling pointer. Set it to NULL.
    head = NULL;

    return 0;
}
```
## 9. File I/O (Input/Output)

File I/O allows your program to read data from and write data to files on the disk, making data persistent between program runs.

### 9.1. Opening, Reading, and Writing Files

The primary functions for file handling are in `<stdio.h>`.

- `fopen(filename, mode)`: Opens a file and returns a `FILE*` pointer. `mode` can be `"r"` (read), `"w"` (write, overwrites), `"a"` (append), `"r+"` (read and write), etc.
- `fclose(file_ptr)`: Closes the file and flushes buffers.
- `fprintf(file_ptr, format, ...)`: Like `printf`, but writes to a file.
- `fscanf(file_ptr, format, ...)`: Like `scanf`, but reads from a file.
- `fgetc(file_ptr)`: Reads a single character from a file.
- `fputc(char, file_ptr)`: Writes a single character to a file.

> [!warning] Always Check `fopen`
> `fopen` returns `NULL` if it fails to open the file (e.g., file doesn't exist in read mode, or permissions are denied). **Always** check for `NULL` before trying to use the file pointer.

```c
#include <stdio.h>
#include <stdlib.h> // For exit()

int main() {
    // --- WRITING TO A FILE ---
    FILE *write_ptr;
    write_ptr = fopen("data.txt", "w"); // Open "data.txt" in write mode

    if (write_ptr == NULL) {
        printf("Error opening file for writing!\n");
        exit(1); // Exit the program with an error code
    }

    fprintf(write_ptr, "Hello, File!\n");
    fprintf(write_ptr, "The answer is %d.\n", 42);

    fclose(write_ptr); // Close the file
    printf("Successfully wrote to data.txt\n");


    // --- READING FROM A FILE ---
    FILE *read_ptr;
    read_ptr = fopen("data.txt", "r"); // Open "data.txt" in read mode

    if (read_ptr == NULL) {
        printf("Error opening file for reading!\n");
        exit(1);
    }

    char buffer[100];
    printf("\n--- Reading from data.txt ---\n");
    // Loop until the end of the file (EOF) is reached
    while (fgets(buffer, sizeof(buffer), read_ptr) != NULL) {
        printf("%s", buffer);
    }

    fclose(read_ptr); // Close the file

    return 0;
}
```

## 10. Advanced Pointer Concepts

### 10.1. Pointers to Pointers (`**`)

A pointer to a pointer is a variable that stores the address of another pointer. This is useful when you need a function to modify a pointer argument itself (e.g., changing which memory address a pointer in the calling function points to).

```c
#include <stdio.h>
#include <stdlib.h>

// This function takes a POINTER TO A POINTER ('int**')
// It can change the 'int*' pointer in the calling function.
void allocateMemoryForInt(int **ptr_to_ptr) {
    // Allocate memory for an integer
    *ptr_to_ptr = (int*)malloc(sizeof(int));

    if (*ptr_to_ptr != NULL) {
        // Assign a value to the newly allocated integer
        **ptr_to_ptr = 99;
    }
}

int main() {
    int *single_ptr = NULL; // Start with a null pointer

    printf("Before function call, single_ptr is NULL\n");

    // Pass the ADDRESS of the pointer
    allocateMemoryForInt(&single_ptr);

    if (single_ptr != NULL) {
        printf("After function call, value is: %d\n", *single_ptr);
        free(single_ptr); // Don't forget to free the allocated memory!
        single_ptr = NULL;
    }

    return 0;
}
```

### 10.2. `const` and Pointers

Using `const` with pointers is important for safety and clarity. The placement of `const` matters.

| Declaration | Meaning |
|---|---|
| `const int *ptr` | Pointer to a `const` integer. You can change the pointer (`ptr`), but you **cannot** change the value it points to (`*ptr`). |
| `int * const ptr` | A `const` pointer to an integer. You can change the value it points to (`*ptr`), but you **cannot** change the pointer itself (`ptr`). |
| `const int * const ptr` | A `const` pointer to a `const` integer. You **cannot** change the pointer or the value it points to. |

```c
#include <stdio.h>

int main() {
    int x = 5, y = 10;

    // 1. Pointer to const data
    const int *ptr1 = &x;
    // *ptr1 = 20; // ERROR: Cannot modify the data through ptr1
    ptr1 = &y;      // OK: Can change the pointer itself
    printf("Value via ptr1: %d\n", *ptr1); // Prints 10

    // 2. Const pointer
    int * const ptr2 = &x;
    *ptr2 = 20;     // OK: Can modify the data
    // ptr2 = &y;  // ERROR: Cannot change the pointer itself
    printf("Value of x is now: %d\n", x); // Prints 20

    return 0;
}
```

## 11. Recursion

Recursion is a programming technique where a function calls itself to solve a problem. A recursive function must have:
1.  A **base case**: A condition that stops the recursion.
2.  A **recursive step**: The part of the function that calls itself, moving towards the base case.

```c
#include <stdio.h>

// Recursive function to calculate factorial
// factorial(n) = n * factorial(n-1)
// Base case: factorial(0) = 1
int factorial(int n) {
    // Base case: if n is 0 or 1, the factorial is 1.
    if (n <= 1) {
        return 1;
    }
    // Recursive step: n * factorial of (n-1)
    else {
        return n * factorial(n - 1);
    }
}

int main() {
    int num = 5;
    printf("Factorial of %d is %d\n", num, factorial(num)); // 120
    return 0;
}
```

> [!caution] Stack Overflow
> Each recursive call adds a new frame to the program's call stack. If the recursion is too deep or the base case is never reached, you can cause a **stack overflow**, crashing your program.

## 12. The C Preprocessor

The preprocessor runs before the compiler. It processes directives that start with `#`.

### 12.1. Macro Functions

You can define function-like macros using `#define`. Be careful, as macros are simple text replacements and can have unexpected side effects.

```c
#include <stdio.h>

// A simple macro to find the maximum of two numbers
// NOTE: The parentheses are crucial to avoid operator precedence issues.
#define MAX(a, b) ((a) > (b) ? (a) : (b))

// A DANGEROUS macro: 'x' is evaluated twice!
#define SQUARE_BAD(x) (x * x)

// A safer macro using a statement expression (GCC/Clang extension) or inline function
// For standard C, an inline function is preferred.
static inline int square_safe(int x) {
    return x * x;
}


int main() {
    int a = 5, b = 10;
    printf("Max of %d and %d is %d\n", a, b, MAX(a, b));

    int result = SQUARE_BAD(a++); // DANGER! 'a++' is evaluated twice.
    printf("Result of SQUARE_BAD(a++): %d\n", result); // Expect 25, but it's 30 (5*6)
    printf("Value of 'a' is now: %d\n", a); // 'a' is 7, not 6!

    int c = 5;
    printf("Result of square_safe(c++): %d\n", square_safe(c++)); // Correctly 25
    printf("Value of 'c' is now: %d\n", c); // 'c' is 6, as expected

    return 0;
}
```

### 12.2. Conditional Compilation

These directives allow you to include or exclude parts of code based on certain conditions. This is very useful for creating different builds (e.g., debug vs. release) or preventing header files from being included multiple times.

```c
#include <stdio.h>

// Define a macro for a debug build
#define DEBUG_MODE 1

void processData() {
    // This code will only be compiled if DEBUG_MODE is defined
    #ifdef DEBUG_MODE
        printf("DEBUG: processData() called.\n");
    #endif

    // ... main processing logic here ...
    printf("Processing data...\n");
}

int main() {
    processData();
    return 0;
}
```

## 13. Bitwise Operators

Bitwise operators manipulate individual bits of an integer. They are often used for low-level programming, setting flags, or optimizations.

| Operator | Name | Description | Example (`x = 6` (110), `y = 3` (011)) |
|---|---|---|---|
| `&` | Bitwise AND | Sets each bit to 1 if both bits are 1. | `x & y` -> `2` (010) |
| `|` | Bitwise OR | Sets each bit to 1 if at least one bit is 1. | `x | y` -> `7` (111) |
| `^` | Bitwise XOR | Sets each bit to 1 if the bits are different. | `x ^ y` -> `5` (101) |
| `~` | Bitwise NOT | Inverts all the bits. | `~x` -> `-7` (in two's complement) |
| `<<` | Left Shift | Shifts bits to the left, filling with zeros. | `x << 1` -> `12` (1100) |
| `>>` | Right Shift | Shifts bits to the right. | `x >> 1` -> `3` (011) |

```c
#include <stdio.h>

int main() {
    unsigned char flags = 0; // 00000000

    // Set the 2nd bit (from the right) using bitwise OR
    unsigned char bit_mask = 1 << 1; // 00000010
    flags = flags | bit_mask;       // flags becomes 00000010

    // Check if the 2nd bit is set using bitwise AND
    if (flags & bit_mask) {
        printf("The 2nd bit is set!\n");
    }

    // Clear the 2nd bit using bitwise AND and NOT
    flags = flags & ~bit_mask;      // flags becomes 00000000
    printf("Flags after clearing: %d\n", flags);

    return 0;
}
```

## 14. Type Definitions (`typedef`) and Enumerations (`enum`)

### 14.1. `typedef`

The `typedef` keyword allows you to create an alias (a new name) for an existing data type. This is extremely useful for simplifying complex type declarations, especially with structs and pointers.

```c
#include <stdio.h>

// Without typedef, you always need 'struct Node'
struct OldNode {
    int data;
    struct OldNode* next;
};

// With typedef, we can create a simpler name 'Node'
typedef struct {
    int data;
    struct Node* next; // Here we can use the alias 'Node' because of the typedef
} Node;

// You can also typedef a pointer type for clarity
typedef Node* NodePtr;

int main() {
    // Old way of declaring a variable
    struct OldNode old_node;

    // New, cleaner way with typedef
    Node new_node;
    NodePtr ptr_node = &new_node; // Using our pointer alias

    new_node.data = 100;
    ptr_node->data = 200; // Accessing via the pointer alias

    printf("Data in new_node: %d\n", new_node.data); // Prints 200

    return 0;
}
```

### 14.2. `enum`

An `enum` (enumeration) is a special type that assigns symbolic names to integer constants, making your code more readable and maintainable.

```c
#include <stdio.h>

// Define an enum for days of the week
// By default, MONDAY = 0, TUESDAY = 1, ..., SUNDAY = 6
typedef enum {
    MONDAY,
    TUESDAY,
    WEDNESDAY,
    THURSDAY,
    FRIDAY,
    SATURDAY,
    SUNDAY
} Weekday;

// You can also assign specific integer values
typedef enum {
    RED = 1,
    GREEN = 2,
    BLUE = 4
} Color;

int main() {
    Weekday today = WEDNESDAY;
    Color favorite_color = BLUE;

    printf("Today's day number: %d\n", today); // Prints 2
    printf("My favorite color's value: %d\n", favorite_color); // Prints 4

    if (today == FRIDAY) {
        printf("TGIF!\n");
    } else {
        printf("Not quite Friday yet.\n");
    }

    return 0;
}
```

## 15. Function Pointers

A function pointer is a variable that stores the address of a function. This allows you to pass functions as arguments to other functions, enabling powerful techniques like callbacks.

> [!tip] `qsort` and Function Pointers
> The most common introductory example for function pointers is the standard library function `qsort`, which sorts an array. It takes a pointer to a "comparison" function that you provide, telling it *how* to sort the elements.

```c
#include <stdio.h>
#include <stdlib.h> // For qsort

// Comparison function for integers for qsort
// qsort requires this specific signature:
// int compare(const void *a, const void *b)
int compareInts(const void *a, const void *b) {
    // Cast the void pointers back to integer pointers and dereference them
    int int_a = *(const int *)a;
    int int_b = *(const int *)b;

    // Return:
    // < 0 if a should come before b
    // > 0 if a should come after b
    // 0 if they are equal
    return (int_a - int_b);
}

// A function that takes another function as an argument
void printNumbers(int *arr, int size, void (*format_func)(int)) {
    for (int i = 0; i < size; i++) {
        // Call the passed-in function
        format_func(arr[i]);
    }
    printf("\n");
}

void standardPrint(int n) {
    printf("%d ", n);
}

void bracketedPrint(int n) {
    printf("[%d] ", n);
}


int main() {
    int numbers[] = {5, 2, 8, 1, 9, 4};
    int n = sizeof(numbers) / sizeof(numbers[0]);

    printf("Original array: ");
    printNumbers(numbers, n, standardPrint);

    // Sort the array using qsort and our comparison function
    qsort(numbers, n, sizeof(int), compareInts);

    printf("Sorted array:   ");
    printNumbers(numbers, n, standardPrint);

    printf("Using a different print function: ");
    printNumbers(numbers, n, bracketedPrint);

    return 0;
}
```

## 16. The C Standard Library (A Deeper Look)

### 16.1. `<stdlib.h>` - General Utilities

Besides `malloc` and `free`, this library contains many other useful functions.

- `atoi(const char *str)`: Converts a string to an integer.
- `atof(const char *str)`: Converts a string to a double.
- `rand()`: Returns a pseudo-random integer between 0 and `RAND_MAX`.
- `srand(unsigned int seed)`: Seeds the random number generator. Use `time(NULL)` to get a different sequence each time.

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h> // For time()

int main() {
    char num_str[] = "123";
    int num = atoi(num_str);
    printf("String \"%s\" as integer: %d\n", num_str, num);

    // Seed the random number generator once at the start of the program
    srand(time(NULL));

    printf("Five random numbers (1-100):\n");
    for (int i = 0; i < 5; i++) {
        // Use the modulo operator to get a number in a specific range
        int random_num = rand() % 100 + 1;
        printf("%d\n", random_num);
    }

    return 0;
}
```

### 16.2. `<math.h>` - Mathematics

Contains common mathematical functions. Remember to link the math library when compiling (e.g., `gcc my_program.c -o my_program -lm`).

- `sqrt(double x)`: Square root.
- `pow(double base, double exp)`: Base raised to the power of exp.
- `sin(double x)`, `cos(double x)`, `tan(double x)`: Trigonometric functions (angle in radians).

```c
#include <stdio.h>
#include <math.h>

int main() {
    double a = 9.0, b = 2.0;

    printf("Square root of %.1f is %.1f\n", a, sqrt(a));
    printf("%.1f to the power of %.1f is %.1f\n", a, b, pow(a, b));

    return 0;
}
```

## 17. Command-Line Arguments

You can pass information to your C program from the command line. The `main` function can be written to accept arguments:

- `int argc`: **A**rgument **c**ount. The number of command-line arguments.
- `char *argv[]`: **A**rgument **v**ector. An array of strings (character pointers) representing the arguments. `argv[0]` is always the program's name.

```c
// Compile with: gcc my_program.c -o my_program
// Run with: ./my_program arg1 arg2 123

#include <stdio.h>

int main(int argc, char *argv[]) {
    printf("Program name: %s\n", argv[0]);
    printf("Number of arguments: %d\n", argc);

    // Loop through the arguments, starting from index 1
    for (int i = 1; i < argc; i++) {
        printf("Argument %d: %s\n", i, argv[i]);
    }

    if (argc < 3) {
        printf("Usage: %s <name> <age>\n", argv[0]);
        return 1; // Indicate an error
    }

    printf("Hello, %s! You are %s years old.\n", argv[1], argv[2]);

    return 0;
}
```

## 18. Advanced Error Handling

When a standard library function fails, it often sets a global integer variable named `errno` (defined in `<errno.h>`) to a specific error code. The `perror()` function can then print a human-readable message for this error.

```c
#include <stdio.h>
#include <stdlib.h>
#include <errno.h> // For errno
#include <string.h> // For strerror

int main() {
    FILE *file_ptr;
    char filename[] = "non_existent_file.txt";

    // Attempt to open a file that doesn't exist
    file_ptr = fopen(filename, "r");

    if (file_ptr == NULL) {
        // perror prints your string, then the system error message for errno
        perror("Error opening file");

        // Alternatively, strerror() returns the error message string
        fprintf(stderr, "Error code %d: %s\n", errno, strerror(errno));

        return 1; // Exit with error
    }

    // ... file operations ...

    fclose(file_ptr);
    return 0;
}
```

## 19. Unions (`union`)

A `union` is a special data type that allows storing different data types in the **same memory location**. A union can only hold one of its members at a time. The size of a union is large enough to hold its largest member.

```c
#include <stdio.h>

// This union can hold either an int, a float, or a char string
// but only one at any given moment.
typedef union {
    int i;
    float f;
    char str[20];
} Data;

int main() {
    Data data;

    data.i = 10;
    printf("data as int: %d\n", data.i);

    data.f = 220.5;
    printf("data as float: %.1f\n", data.f);

    // If we try to read data.i now, the value is corrupted
    // because the memory was overwritten by the float.
    printf("data as int (after float assignment): %d\n", data.i);

    strcpy(data.str, "Hello C");
    printf("data as string: %s\n", data.str);

    printf("Size of Data union: %zu bytes\n", sizeof(Data)); // Will be 20 (size of str[20])

    return 0;
}
```

## 20. Multi-File Projects and Header Guards

As programs grow, placing all code in a single file becomes unmanageable. The standard practice is to split code into multiple **source files (`.c`)** and **header files (`.h`)**.

-   **Header Files (`.h`)**: Contain declarations, such as function prototypes, `struct` definitions, `typedef`s, and `extern` variable declarations. They act as the "interface" to a module.
-   **Source Files (`.c`)**: Contain the actual definitions (the code) for the functions declared in the corresponding header file.

> [!important] Header Guards
> To prevent a header file from being included multiple times in the same compilation unit (which causes redefinition errors), you must wrap its contents in **header guards**.

### Example: A Simple Math Utilities Module

**File: `math_utils.h`** (The Interface)
```c
#ifndef MATH_UTILS_H // "if not defined"
#define MATH_UTILS_H // "then define it"

// Function prototypes
int add(int a, int b);
int multiply(int a, int b);

#endif // End of the guard
```

**File: `math_utils.c`** (The Implementation)
```c
#include "math_utils.h" // Include our own header to ensure consistency

// Function definitions
int add(int a, int b) {
    return a + b;
}

int multiply(int a, int b) {
    return a * b;
}
```

**File: `main.c`** (The User of the Module)
```c
#include <stdio.h>
#include "math_utils.h" // Include the interface to use the functions

int main() {
    int x = 5, y = 10;
    printf("%d + %d = %d\n", x, y, add(x, y));
    printf("%d * %d = %d\n", x, y, multiply(x, y));
    return 0;
}
```

**To Compile a Multi-File Project:**
You must compile all `.c` files together.
```bash
gcc main.c math_utils.c -o my_program
```

## 21. Advanced String Manipulation

The `<string.h>` library provides more functions for working with strings.

-   `strcat(dest, src)`: Appends (concatenates) the `src` string to the end of the `dest` string.
-   `strcmp(s1, s2)`: Compares two strings lexicographically (alphabetically). Returns `< 0` if `s1` comes before `s2`, `0` if they are equal, and `> 0` if `s1` comes after `s2`.
-   `strtok(str, delim)`: Breaks a string into a series of tokens based on a set of delimiter characters.

> [!warning] Buffer Overflows
> Functions like `strcat` and `strcpy` do not check the size of the destination buffer. Writing past the end of a buffer causes a **buffer overflow**, a common security vulnerability. Use safer versions like `strncat` and `strncpy` where possible.

```c
#include <stdio.h>
#include <string.h>

int main() {
    // --- strcat ---
    char first[50] = "Hello, ";
    char second[] = "World!";
    strcat(first, second);
    printf("Concatenated: %s\n", first); // "Hello, World!"

    // --- strcmp ---
    char s1[] = "apple";
    char s2[] = "banana";

    if (strcmp(s1, s2) < 0) {
        printf("\"%s\" comes before \"%s\"\n", s1, s2);
    }

    // --- strtok ---
    char sentence[] = "This is a sentence with words.";
    char *token;
    const char delimiter[2] = " ";

    // Get the first token
    token = strtok(sentence, delimiter);
    printf("Tokens:\n");

    // Walk through other tokens. Pass NULL to continue from the last spot.
    while (token != NULL) {
        printf("%s\n", token);
        token = strtok(NULL, delimiter);
    }

    return 0;
}
```

## 22. Advanced Dynamic Memory Allocation

Besides `malloc`, the standard library provides `calloc` and `realloc`.

-   `calloc(num, size)`: **C**ontiguous **alloc**ation. Allocates memory for an array of `num` elements, each of `size` bytes, and **initializes all bytes to zero**.
-   `realloc(ptr, new_size)`: **Re**-**alloc**ation. Changes the size of the memory block pointed to by `ptr` to `new_size`. It may move the block to a new location.

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    // --- calloc ---
    // Allocate an array of 5 integers, initialized to 0
    int *calloc_arr = (int*)calloc(5, sizeof(int));
    if (calloc_arr == NULL) { /* handle error */ }

    printf("calloc array (all zeros):\n");
    for (int i = 0; i < 5; i++) {
        printf("%d ", calloc_arr[i]); // Will print "0 0 0 0 0 "
    }
    printf("\n");
    free(calloc_arr);

    // --- realloc ---
    // Start with an array of 3 integers
    int *realloc_arr = (int*)malloc(3 * sizeof(int));
    realloc_arr[0] = 10; realloc_arr[1] = 20; realloc_arr[2] = 30;

    // Resize the array to hold 5 integers
    int *temp = (int*)realloc(realloc_arr, 5 * sizeof(int));
    if (temp != NULL) {
        realloc_arr = temp; // Reassign only if successful
        realloc_arr[3] = 40;
        realloc_arr[4] = 50;

        printf("realloc array after resizing:\n");
        for (int i = 0; i < 5; i++) {
            printf("%d ", realloc_arr[i]); // "10 20 30 40 50 "
        }
        printf("\n");
    } else {
        // realloc failed, original realloc_arr is still valid
        free(realloc_arr);
    }

    free(realloc_arr);
    return 0;
}
```

## 23. The `static` Keyword

The `static` keyword has two distinct meanings depending on its context.

### 23.1. Static Local Variables
Inside a function, a `static` local variable retains its value between function calls. It is initialized only once.

```c
#include <stdio.h>

void counter() {
    // This variable is created and initialized only once.
    // Its value persists across calls to counter().
    static int count = 0;
    count++;
    printf("This function has been called %d time(s).\n", count);
}

int main() {
    counter(); // Prints 1
    counter(); // Prints 2
    counter(); // Prints 3
    return 0;
}
```

### 23.2. Static Global Variables and Functions
When used on a global variable or a function outside of any function, `static` limits its visibility to the **current file only**. This is called **internal linkage**. It's useful for creating helper functions that shouldn't be accessible from other parts of a large program.

```c
// In file: helper.c
static int secret_variable = 100; // Only visible within helper.c

static void helper_function() { // Only callable from within helper.c
    printf("This is a private helper.\n");
}

void public_function() {
    helper_function(); // This is OK
    printf("The secret is %d\n", secret_variable);
}

// In file: main.c
// void public_function(); // We would need a prototype for this

int main() {
    public_function();
    // helper_function(); // ERROR: 'helper_function' is not visible here.
    // printf("%d\n", secret_variable); // ERROR: 'secret_variable' is not visible.
    return 0;
}
```

## 24. The `volatile` Keyword

The `volatile` keyword is a type qualifier that tells the compiler that a variable's value may be changed in ways outside the control or detection of the program (e.g., by a hardware device in an embedded system). This prevents the compiler from making optimizations that might assume the variable's value doesn't change unexpectedly.

```c
// Conceptual example: A hardware timer register
volatile int *timer_register = (int*)0x1000;

void check_timer() {
    // Without 'volatile', the compiler might optimize this loop
    // into an infinite loop if it thinks *timer_register can't change.
    while (*timer_register == 0) {
        // Wait for the timer to be triggered by hardware
    }
}
```

## 25. Variable Scoping and Storage Duration

Understanding where a variable is visible (**scope**) and how long it exists (**storage duration**) is crucial for writing correct and predictable programs.

### 25.1. Scope

-   **Block Scope**: Variables declared inside a block `{ ... }` (e.g., inside a function, loop, or `if` statement) are only accessible within that block.
-   **File Scope**: Variables declared outside of any function (global variables) are accessible from any point in the file *after* their declaration. If declared as `static`, they have file scope but are not accessible from other files.
-   **Function Prototype Scope**: The names of parameters in a function prototype are only visible within the prototype itself.

```c
#include <stdio.h>

int global_var = 100; // File Scope

void myFunction() {
    int local_var = 10; // Block Scope
    printf("Inside function: global_var = %d, local_var = %d\n", global_var, local_var);
}

int main() {
    int local_var = 20; // A different local_var, also Block Scope

    if (1) {
        int block_var = 5; // Block Scope, only inside this if-block
        printf("Inside if-block: block_var = %d\n", block_var);
    }
    // printf("%d\n", block_var); // ERROR: block_var is not visible here

    printf("In main: global_var = %d, local_var = %d\n", global_var, local_var);
    myFunction();

    return 0;
}
```

### 25.2. Storage Duration & Specifiers

-   **Automatic Storage Duration** (`auto`): The default for local variables. They are created when the block is entered and destroyed when the block is exited. The `auto` keyword is almost never used explicitly.
-   **Static Storage Duration** (`static`): The variable exists for the entire lifetime of the program.
    -   When applied to a local variable, it retains its value between function calls (see [[#23. The `static` Keyword]]).
    -   When applied to a global variable/function, it gives it **internal linkage**, making it private to the file.
-   **Dynamic Storage Duration**: Memory allocated with `malloc`, `calloc`, or `realloc`. It exists until it is explicitly deallocated with `free`.
-   **External Linkage** (`extern`): This keyword is used to *declare* a global variable that is *defined* in another file. It tells the compiler, "This variable exists, but the memory for it is allocated elsewhere."

**Example of `extern`**

**File: `config.c`**
```c
// Definition of the global variable. Memory is allocated here.
int app_config_value = 42;
```

**File: `main.c`**
```c
#include <stdio.h>

// Declaration of the variable. It tells main.c about the variable
// defined in config.c. No memory is allocated by this line.
extern int app_config_value;

int main() {
    // We can now use the variable from another file.
    printf("The configuration value is: %d\n", app_config_value);
    return 0;
}
```

**To Compile:**
```bash
gcc main.c config.c -o my_program
```

## 26. Number Systems: Binary and Hexadecimal

While we use decimal (base 10) in daily life, computers operate in binary (base 2). Hexadecimal (base 16) is a convenient shorthand for representing binary data.

### 26.1. Binary (Base 2)

-   Uses only 0 and 1.
-   Each digit is called a **bit**.
-   8 bits make a **byte**.
-   **Relevance:** Bitwise operators (`&`, `|`, `^`, `<<`, `>>`) directly manipulate the binary representation of numbers. Understanding binary is key to using them effectively.

**Example:** The number `13` in binary is `00001101`.
`(8 * 1) + (4 * 1) + (2 * 0) + (1 * 1) = 13`

### 26.2. Hexadecimal (Base 16)

-   Uses digits 0-9 and letters A-F.
-   `A=10`, `B=11`, `C=12`, `D=13`, `E=14`, `F=15`.
-   **Relevance:** One hex digit represents exactly 4 bits (a **nibble**). This makes it perfect for representing memory addresses and byte-level data in a compact, human-readable form.

| Binary | Hex | Decimal |
|---|---|---|
| `0000` | `0` | 0 |
| `1010` | `A` | 10 |
| `1111` | `F` | 15 |
| `00001101` | `0D` | 13 |
| `11111111` | `FF` | 255 |

### 26.3. Using Hex and Binary Literals in C

Modern C (C99 and later) allows you to write numbers directly in these bases.

-   **Hexadecimal Prefix:** `0x` or `0X`
-   **Binary Prefix:** `0b` or `0B` (part of C++14 and a common GCC/Clang extension, not standard C until C23, but widely supported).

```c
#include <stdio.h>

int main() {
    int dec = 13;
    int hex = 0x0D;  // Hexadecimal for 13
    int bin = 0b1101; // Binary for 13

    printf("Decimal: %d\n", dec);
    printf("Hex: %d\n", hex);
    printf("Binary: %d\n", bin);

    // To print in these formats, use format specifiers:
    printf("Value %d is 0x%X in hex.\n", dec, dec); // %X for uppercase hex
    // Note: There is no standard printf specifier for binary.

    return 0;
}
```

## 27. Common Pitfalls and Best Practices

C is a powerful but unforgiving language. Many bugs stem from a few common mistakes. Being aware of them is the first step to writing better code.

### 27.1. Buffer Overflows

This is one of the most dangerous and common security vulnerabilities in C. It occurs when you write data past the end of an allocated block of memory (like an array).

-   **Cause**: Using unsafe functions like `strcpy`, `sprintf`, `gets` (never use `gets`), or incorrect loop bounds.
-   **Prevention**: Use safe functions that limit the number of characters written, like `strncpy`, `snprintf`, and `fgets`. Always be mindful of array sizes.

```c
#include <stdio.h>
#include <string.h>

int main() {
    char buffer[10];

    // DANGEROUS: strcpy does not check the size of 'buffer'.
    // If src is larger than 9 chars (+1 for '\0'), it will overflow.
    // strcpy(buffer, "This string is way too long"); // CRASH!

    // SAFE: strncpy limits the number of characters copied.
    // We copy at most 9 characters, leaving room for the null terminator.
    strncpy(buffer, "This string is way too long", 9);
    buffer[9] = '\0'; // IMPORTANT: strncpy doesn't guarantee null-termination

    printf("Buffer contents: %s\n", buffer); // "This stri"

    return 0;
}
```

### 27.2. Memory Leaks

A memory leak happens when you allocate memory on the heap with `malloc` (or `calloc`/`realloc`) but forget to free it with `free`. The program's memory usage grows over time, which can crash the system.

-   **Cause**: Forgetting to call `free()` for every `malloc()`.
-   **Prevention**: For every `malloc`, there must be a corresponding `free`. A good rule of thumb is to `free` memory in the same scope where it was allocated, or to have a clear "destroy" function for complex data structures.

```c
void create_leak() {
    // Memory is allocated, but the function 'leaks' it
    // because it's never freed.
    int *leaky_ptr = (int*)malloc(sizeof(int));
    *leaky_ptr = 100;
    printf("Leaky pointer points to: %d\n", *leaky_ptr);
    // Function ends, leaky_ptr is destroyed, but the 4 bytes on the heap remain!
}

void no_leak() {
    int *safe_ptr = (int*)malloc(sizeof(int));
    *safe_ptr = 200;
    printf("Safe pointer points to: %d\n", *safe_ptr);

    free(safe_ptr); // The memory is correctly released.
    safe_ptr = NULL; // Good practice to avoid dangling pointers.
}
```

### 27.3. Dangling Pointers

A dangling pointer is a pointer that points to memory that has been freed or is no longer valid. Dereferencing a dangling pointer leads to **undefined behavior**—it might work, it might crash, or it might silently corrupt data.

-   **Cause**: Accessing memory after `free`ing it, or returning a pointer to a local variable from a function.
-   **Prevention**: Set a pointer to `NULL` immediately after you `free` it. Never return the address of a local variable.

```c
#include <stdio.h>
#include <stdlib.h>

int* bad_function() {
    int local_var = 10;
    return &local_var; // ERROR: Returning address of a local variable!
}

int main() {
    int *ptr = (int*)malloc(sizeof(int));
    *ptr = 50;
    printf("Before free: %d\n", *ptr);

    free(ptr);
    // ptr is now a DANGLING POINTER.

    // DANGEROUS: Dereferencing a dangling pointer. This is undefined behavior.
    // printf("After free: %d\n", *ptr); // MIGHT CRASH OR PRINT GARBAGE

    ptr = NULL; // Good practice
    // Now, dereferencing ptr will cause a predictable crash (segmentation fault),
    // which is much easier to debug.
    // printf("After nulling: %d\n", *ptr); // PREDICTABLE CRASH

    int *dangle = bad_function(); // dangle is now a dangling pointer
    // printf("%d\n", *dangle); // UNDEFINED BEHAVIOR

    return 0;
}
```

### 27.4. Off-by-One Errors

A classic logic error where you iterate one time too many or one time too few. This is common with loops and array indexing.

-   **Cause**: Using incorrect loop conditions, like `i <= size` instead of `i < size` when iterating through an array of `size` elements.
-   **Prevention**: Be meticulous with loop bounds. Remember that C arrays are 0-indexed, so a 5-element array has valid indices `0, 1, 2, 3, 4`.

```c
#include <stdio.h>

int main() {
    int arr[5] = {1, 2, 3, 4, 5};

    // Correct loop: iterates from index 0 to 4
    printf("Correct loop:\n");
    for (int i = 0; i < 5; i++) {
        printf("arr[%d] = %d\n", i, arr[i]);
    }

    // Off-by-one error: iterates from index 0 to 5
    // arr[5] is out of bounds! This is undefined behavior.
    printf("\nOff-by-one error:\n");
    for (int i = 0; i <= 5; i++) {
        printf("arr[%d] = %d\n", i, arr[i]); // DANGER on the last iteration
    }

    return 0;
}
	```