```java
public static int min(int[] numbers) {
    int min = numbers[0];
    for (int i = 1; i < numbers.length; i++) {
        int currentNumber = numbers[i];
        if (currentNumber < min) {
            min = currentNumber;
        }
    }
    return min;
}
```

```java
package shapes;

public class Rectangle extends Shape {
    public double a;
    private double b;



    public Rectangle(double a, double b) {
        this.a = a;
        this.b = b;
    }
    public double computeArea() {
        return a * b;
    }
    @Override
    public double computePerimeter() {
        return 2 * (a + b);
    }

    @Override
    public int edgeCount() {
        return 4;
    }
}
```
