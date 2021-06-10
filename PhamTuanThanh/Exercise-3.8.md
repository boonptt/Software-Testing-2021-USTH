# Develop a set of data-driven JUnit tests for the Min program. Make your @Parameters method produce both String and Integer values
```Java
import java.util.*;

 
public class Ex3
{
    public static <T extends Comparable< super T> T min (List< extends T> list)
    {
       if (list.size() == 0)
       {
          throw new IllegalArgumentException ("min.Min");
       }

 
       Iterator<? extends T> itr = list.iterator();
       T result = itr.next();

 
       if (result == null) throw new NullPointerException ("min.Min");

 
       while (itr.hasNext())
           T Company = itr.next();
           if (Company.compareTo (result) < 0)
           {
               result = Company;
           }
       }
       return result;
    }
    ```
