Instructions
Create a file ListEqual.java.

Write a function areListEquals that returns true if the lists as parameters are equals. Returns false otherwise.

Expected Functions
import java.util.List;

``` java
public class ListEqual {
    public static boolean areListEquals(List<String> list1, List<String> list2) {
        // your code here
    }
}
```
Usage
Here is a possible ExerciseRunner.java to test your function :

import java.util.List;

``` java
public class ExerciseRunner {
    public static void main(String[] args) {
        System.out.println(ListEqual.areListEquals(List.of("Alice", "Bob", "Charly", "Emily"), List.of("Alice", "Bob", "Charly", "Emily")));
        System.out.println(ListEqual.areListEquals(List.of("Alice", "Bob", "Charly", "Emily"), List.of("Alice", "Bob", "Emily", "Charly")));
    }
}
```
and its output :

``` bash
$ javac *.java -d build
$ java -cp build ExerciseRunner 
true
false
$ 
```