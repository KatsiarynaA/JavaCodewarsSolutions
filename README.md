# JavaCodewarsSolutions

* https://www.codewars.com/kata/fibonacci/train/haskell

```java
public class Fibonacci {
  public static long fib(int n) {
    long f0 = 0;
    long f1 = 1;
    long f2 = 1;
    if (n == 0) return f0;
    if (n == 1) return f1;
    for (int i = 2; i <= n; i++) {
      f2 = f0 + f1;
      f0 = f1;
      f1 = f2;
    }
    return f2;
  }
}
```