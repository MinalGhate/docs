---
Title: '.max()'
Description: 'Returns the maximum value from the given two arguments.'
Subjects:
  - 'Computer Science'
Tags:
  - 'Methods'
  - 'Function'
  - 'Arithmetic'
CatalogContent:
  - 'learn-java'
  - 'paths/computer-science'
---

The **`Math.max()`** method returns the maximum value from the given two arguments.

## Syntax

```pseudo
Math.max(num1, num2)
```
- The `.max()` function takes two parameters `num1` and `num2`.
- The `num1` and `num2` arguments can be of type int, float, double or long.

## Example

The following example uses the `.max()` method to print the maximum of two numbers:

```java
public class Main {
    public static void main(String[] args){
        int num1 = 50;
        int num2 = 10;

        System.out.println(Math.max(num1, num2));
    }
}
```

This results in the following output:

```java
50
```