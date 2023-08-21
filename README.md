# Java-Syntax and introduction :
1. To find out what is JDK, JRE and JVM :
    *you can access this link : [https://s.net.vn/o0tY]
2. An instant noodle for learning Java when you already learnt other programming languages 
Format prints "hello world" :
```python
    class HelloWorld{
        public static void main(String args[]){
              System.out.println("Hello World!");
        } 
  }
```

*take note : "println" can help the content in column while "print" works like "display : flex in CSS" which is a row.*

# Level 1: Java- Variables and Primitive Data Types

There are four kinds of variables :

  +Instance Variables
  
  +Instance Variables
  
  +Local Variables 
  
  +Parameters

  - int : integer number (ex : int speed = 80 ). It values from -2^31 to 2^31 - 1
```python
class number {
    public static void main(String[] args) {
        
        int a = 23;
        System.out.println(a);
    }
}
OUTCOME : 23
```   
  - boolean : set variable true or false

```python
class BooleanVariable {
    public static void main(String[] args) {
        
        boolean answer = true;
        System.out.println(answer);
    }
}
```
OUTCOME : true
  - byte : replaced for "int" to save memory if data is between [-121,127]
  - short : same as byte, but the value is between [-32768, 32767]
  - long : same, the value is between -2^63 and 2^63 - 1.
    => long myvariable = 4526354632L
    *The L at the end of the number 42332200000 is inseparable. It represents data of variable long*
  - double : decimal number with 64 bit
    => double myvariable = 4.5d
  -  float : same as double, but it values 32 bit.
  -  char : this one is used for single letters liek 'a' or $,# etc... and unicode.
    => char myvariable = 'h'
    => char myunicode = '\u0000' means 'Q'
     *you can check GG for unicode table in java*
  


