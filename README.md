# unit-2-5-assignment

## API and Documentation
Documentation for the shape classes can be found [here](https://coderunner.projectstem.org/docs/shapes/index.html).

## Git Config
```
git config user.name "user"
git config user.email "email"
```

## Compiling and Running Java Programs
Note that since the shape classes are separate classes, you will need to compile ALL the files (at least one time).  You can do this by running
```
javac *.java
```
The star means to compile every file that is a Java file type.

Run your code by running
```
java Main.java
```

After you compile the shape classes, you only need to compile and run `Main.java` as usual.

## Problem 1
Write code which creates three circles with radius 10.1, 14 and 20.5 respectively. The code should then print the three circles, one on each line, in the order given (i.e. the one with radius 10.1 first and the one with radius 20.5 last). To print the results, use the `toString()` method for the `Circle` class.

For example
```java
Circle circ1 = /* code not shown */
System.out.println(circ1.toString());  // produces desired output

// alternatively
String output = circ1.toString();
System.out.println(output);
```

Sample run:
```
circle with radius 10.1
circle with radius 14.0
circle with radius 20.5
```

## Problem 2
Write code which takes three decimal inputs from the user, creates a rectangle with length and width equal to the first input and a rectangle with length and width equal to the second and third input respectively, then prints both of these shapes. To print the results, use the `toString()` method for the `Rectangle` class. 

Sample run:
```
Type a number for length and width:
2.6
Type a length:
10.4
Type a width:
28.9
rectangle with length 2.6, width 2.6
rectangle with length 10.4, width 28.9
```
