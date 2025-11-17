# Compare Two Numbers (If/Else vs Ternary Operator)

This example shows how to compare two numbers in two different ways in C#:
1. Using a normal if/else statement  
2. Using a one-line ternary operator (?:)

---

## Method 1 — Using if / else

```csharp
// Two sample numbers
int a = 10;
int b = 20;

// Compare the values using a standard if/else statement
if (a > b)
{
    // If 'a' is greater, print 'a'
    Console.WriteLine("The bigger number is: " + a);
}
else
{
    // Otherwise, print 'b'
    Console.WriteLine("The number is smaller or equal: " + b);
}

## ** Method 2 — One-Line Version (Ternary Operator)**

// Two sample numbers
int a = 10;
int b = 20;

// One-line conditional check using the ternary operator
Console.WriteLine(
    a > b
        ? "The bigger number is: " + a    // Runs if 'a' is bigger
        : "The number is smaller or equal: " + b  // Runs if not
);

