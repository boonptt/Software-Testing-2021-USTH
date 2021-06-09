# Excercise 1.4 #

## a) Write a Java method with the signature
```Java
import java.util.vector;

class vector_test {
    public static vector union (vector a, vector b) {
        vector v = new vector();
        v.addAll(A);
        v.addAll(B);
        return v;
    }
    public static void main(String[] args) {
        vector A = new Vector();
        A.add(10);
        vector B = new Vector();
        B.add(8);
        vector v = union(A, B);
    }
}
```

## b) 
One of possible error is lack of verification statements such as checking the two vectors are empty or have different dimensions.

## c)
```Java
vector A = new vector()
vector B = new vector()
```
```Java
vector A = new vector();
A.add(10)
vector B = new vector();
```
```Java
vector A = new vector();
vector B = new vector();
B.add(8)
```

        
