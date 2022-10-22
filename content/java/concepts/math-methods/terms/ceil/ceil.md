---
Title: '.ceil()'
Description: 'Returns the double value that is greater than or equal to argument.'
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

The **`Math.abs()`** method returns the double value that is greater than or equal to argument.

## Syntax

```pseudo
Math.ceil(num)
```

- The `.ceil()` function takes a single parameters `num`.

## Example

The following example uses `.ceil()` method to print the ceiling values of `6.5`, `3`, and `-6.5`:

```java
class Main {
  public static void main(String[] args) {
    
    System.out.println(Math.ceil(6.5));
    System.out.println(Math.ceil(3));
    System.out.println(Math.ceil(-6.5));
  }
}
```

This results in the following output:

```shell
7.0
3.0
-6.0
```
