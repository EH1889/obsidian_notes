In [[Programming]] Java is a a high-level, class-based, oop that is designed to have as few dependencies as possible.

Developed by James Gosling at Sun Microsystems it was released in May of 1995.

As of July 2023, OpenJDK is the opensource Java IDE

I installed Java on the mac under brew, so 
```
brew info openjdk
```

From W3schools
Left off at Java stirngs

Java is case sensitive 
Primitive Data types are: byte, short, long, double int, float, char,
Non-primitive Data types include: boolean, String // note String is uppercase, boolean is spelled out

Non-primitive types can be null

comments
```
//single line//

/* multi
line */
```

var
```
String myStr = "Var"
Int myInt = 120
```
print
```
System.out.println();
```
single lines are seperated by commas
```
int x = 5, y =6, z = 7;
System.out.pritln(x+y+z);
```
For Narrowing type casting use the data type in paraenths
```
int myInt = (int) myDouble
```


every line code in java must be in a class, the class should begin with an Upper char

public class Main{}