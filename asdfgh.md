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
