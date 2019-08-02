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

* https://www.codewars.com/kata/playing-with-cubes-i/train/java

```java
public class Cube {

  private int side;

  public int getSide() {
    return side;
  }

  public void setSide(int side) {
    this.side = side;
  }
}
```

* https://www.codewars.com/kata/lombok-encapsulation/train/java

```java
public class EncapsulationDemo {

    private int number;

    private  String stringValue;

    private  Object anObject;

    public int getNumber() {
        return number;
    }

    public void setNumber(int number) {
        this.number = number;
    }

    public String getStringValue() {
        return stringValue;
    }

    public void setStringValue(String stringValue) {
        this.stringValue = stringValue;
    }

    public Object getAnObject() {
        return anObject;
    }

    public void setAnObject(Object anObject) {
        this.anObject = anObject;
    }

    public EncapsulationDemo() {
    }

    public EncapsulationDemo(int number, String stringValue, Object anObject) {
        this.number = number;
        this.stringValue = stringValue;
        this.anObject = anObject;
    }
}
```