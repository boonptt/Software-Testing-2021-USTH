# Calc.java
```Java
package com.Company;

public class Calc {
    static public int add(int x, int y) {
        return x + y;
    }

    static public int subtract(int x, int y) {
        return x - y;
    }

    static public int multiply(int x, int y) {
        return x * y;
    }

    static public double divide (int x, int y)
    {
        return (float) x/y;
    }
}
```

# Test.java
```Java
import org.junit.Test;
import static org.junit.Assert.*;

public class Test {
    Calc calc = new Calc();
    private int x = 1;
    private int y = 1;

    @Test
    public void testadd() {
        assertEquals(calc.add(x, y), 2);
    }

    @Test
    public void testsubtract() {
        assertEquals(calc.substract(x, y), 0);
    }

    @Test
    public void testmultiply() {
        assertEquals(calc.multiply(x, y), 1);
    }

    @Test
    public void testdivide() {
        assertEquals(calc.divide(x, y), 1);
    }
}
```
