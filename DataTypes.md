# Java Basics

### Two Data Types:
- Primitive
- Non Primitive

### Primitive Data Types:
- int -> 4 bytes, 32 bits
- long -> 8 bytes, 64 bits
- short -> 2 bytes, 16 bits
- float -> 4 bytes, 32 bits
- double -> 8 bytes, 64 bits
- byte -> 1 byte, 8 bits
- char -> 2 bytes, 16 bits
- boolean -> true/false

### Non Primitive Data Types
- String
- Array
- Class -> Blueprint for creating objects, with state (member variables) and behavior (methods).
- Interface -> It is a collection of abstract methods.
- Enum -> A set of named values (days of a week).
- Record -> To define a "carrier" of data. (Folder of data)


```
public class DataTypes {
    public static void main(String[] args) {
        int x = 5;
        double y = 3.14;
        float z = 2.718f;
        long w = 1234567890L;
        short v = 32767;
        byte u = 127;
        char c = 'A';
        boolean b = true;

        String str = "Hello World";
        int[] nums = {1, 2, 3, 4, 5};
        String[] names = {"John", "Mary", "Bob"};
    }
}
```


### Wrapper classes

- All primitive types have a corresponding wrapper class.

##### Creating a wrapper class

```
int i = 10;

Integer intWrapper = new Integer(i);
Integer i = 10;
```