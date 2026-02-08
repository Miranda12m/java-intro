<h1>My Java Cheat Sheet</h1>

<p>A concise cheat sheet for Java beginners covering prints, variables, arithmetic operators, if statements, loops, input handling and more :D</p>

<hr>

<h2>🖨️ Printing (Output)</h2>

```java
System.out.print("Hello");          // prints without new line
System.out.println("Hello");        // prints with new line
System.out.printf("Age: %d%n", 20); // formatted output
```

<p><strong>Format specifiers:</strong> %d → integer, %f → float/double, %s → string, %n → newline</p>

<hr>

<h2>📦 Variables & Data Types</h2>

```java
int age = 25;
double price = 19.99;
char grade = 'A';
boolean isJavaFun = true;
String name = "Alex";

// Constants
final int MAX_SCORE = 100;
```

<hr>

<h2>➗ Arithmetic Operators</h2>

```java
int a = 10;
int b = 3;

a + b;  // addition
a - b;  // subtraction
a * b;  // multiplication
a / b;  // integer division
a % b;  // modulus

// Increment / Decrement
a++; // a = a + 1
a--; // a = a - 1
```

<hr>

<h2>⚖️ Comparison Operators</h2>

```java
a == b; // equal
a != b; // not equal
a > b;  // greater than
a < b;  // less than
a >= b; // greater or equal
a <= b; // less or equal
```

<hr>

<h2>🔀 Logical Operators</h2>

```java
&&  // AND
||  // OR
!   // NOT

// Example
if (age >= 18 && age <= 65) {
    System.out.println("Working age");
}
```

<hr>

<h2>🔍 If / Else Statements</h2>

```java
if (condition) {
    // code
} else if (anotherCondition) {
    // code
} else {
    // code
}

// Example
int score = 85;

if (score >= 90) {
    System.out.println("A");
} else if (score >= 80) {
    System.out.println("B");
} else {
    System.out.println("C or lower");
}
```

<hr>

## 🔁 Loops

### For Loop
```java
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}
```

### While Loop
```java
int i = 0;
while (i < 5) {
    System.out.println(i);
    i++;
}
```

### Do-While Loop
```java
int i = 0;
do {
    System.out.println(i);
    i++;
} while (i < 5);
```

### Enhanced For Loop (For-Each)
```java
int[] numbers = {1, 2, 3, 4};

for (int n : numbers) {
    System.out.println(n);
}
```

### Loop Control
```java
break;    // exit loop
continue; // skip current iteration
```

<hr>

<h2>📝 Input Handling</h2>

```java
import java.util.Scanner;

Scanner scanner = new Scanner(System.in);

System.out.print("Enter your name: ");
String name = scanner.nextLine();

System.out.print("Enter your age: ");
int age = scanner.nextInt();

System.out.println("Hello " + name + ", you are " + age + " years old!");
```

<hr>

<h2>🧠 Basic Structure of a Java Program</h2>

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

<p>Everything here can be used as a reference for writing simple Java programs, learning basic syntax, and practicing with inputs.</p>