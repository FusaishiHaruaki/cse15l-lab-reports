# CSE 15L Wi23 Lab Report 2

## Part1 


## Part2
`reverse` method in `ArrayTests` class:

Faliure induce input with jUnit testing: 

```
import static org.junit.Assert.*;
import org.junit.*;

public class ArrayTests {
  @Test
  public void testReversed() {
    int[] input1 = {1, 2};
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
}
```

Input that doesn't induce a failure:

```
import static org.junit.Assert.*;
import org.junit.*;

public class ArrayTests {
  @Test
  public void testReversed() {
    int[] input1 = {0, 0};
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
}
```

Symptom: 
[Image](/img/reportImages-2/part2-failed-junitTest.png)

## Part3


