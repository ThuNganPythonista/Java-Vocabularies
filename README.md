# Java introduction :
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
  
  +Class Variables
  
  +Local Variables 
  
  +Parameters

  - int : integer number (ex : int speed = 80 ). It values from -2^31 to 2^31 - 1
```python
class Ngan {
    public static void main(String[] args) {
        
        int a = 23;
        System.out.println(a);
    }
}
OUTCOME : 23
```   
  - boolean : set variable true or false

```python
class Ngan {
    public static void main(String[] args) {
        
        boolean answer = true;
        System.out.println(answer);
    }
}
```
OUTCOME : true
  - byte : replaced for "int" to save memory if data is between [-121,127]

```python
class Ngan {
    public static void main(String[] args) {
        byte test;
        test = 009;
        System.out.println(test);
    }
}
```
OUTCOME : 009
  - short : same as byte, but the value is between [-32768, 32767]

```python
class Ngan {
    public static void main(String[] args) {
        
        short tem = -330;
        System.out.println(tem);
    }
}
```
OUTCOM : -330
  - long : same, the value is between -2^63 and 2^63 - 1.
```python    
   class Ngan {
       public static void main(String[] args) {
        
        long bignum = 4526354632L;
        System.out.println(bignum);
    }
}
```
OUTCOME :4526354632

*The L at the end of the number 42332200000 is inseparable. It represents data of variable long*
    
  - double : decimal number with 64 bit
```python    
   class Ngan {
       public static void main(String[] args) {
        
        double decimal = 14.5d;
        System.out.println(decimal);
    }
}
```
    => double decimal = 14.5d
  -  float : same as double, but it values 32 bit.

```python    
   class Ngan {
       public static void main(String[] args) {
        
        float decimal =-6.9;
        System.out.println(bignum);
    }
}
```
  -  char : this one is used for single letters liek 'a' or $,# etc... and unicode.
    
```python    
   class Ngan {
       public static void main(String[] args) {
        
        char single-word ='h';
        System.out.println(single-word);
    }
}
```
OUTCOME : h

    => char myunicode = '\u0000' means 'Q'
```python    
   class Ngan {
       public static void main(String[] args) {
        
        char single-word ='\u0041\';
        System.out.println(single-word);
    }
}
```
*You can check GG for unicode table in java*

     
  # Level 2 : Java literals

  Hmm what is "literals" ? Let's take a look

  `int number = 8`

  + int : data type
  + number : variable
  + 8  : LITERAL

    Any fixed values will be put in open source of the program, and it's no need to evaluate or calculate.

##### Integer literals #####

- Integer literals are data types : byte, int, long, short 

##### Hexadecimal Literal (0x) : the base-16 number system #####
   + digits : 0 --> 9
   + A-F    : 0 --> 15

 => For example : Ox1F is 31

  #####  WHY? WHY 1F = 31 #####

  1 is in the index position of 1 from the right --> 1 * 16^1 = 16
  F is in the index position of 0 from the right --> 15 * 16^0 = 15

             15+16 = 31
             
`int hexadecimal = 0xF2`

2 is in the index position of 0 from the right --> 2 * 16^0 = 2
F is in the index position of 1 from the right --> 15 * 16^1 = 240

         240 + 2 = 242 
  
##### Binary Literal (0b) : the base-2 number system #####

- Digits 0 and 1 only

  ==> For example : 0b10010

  Now we start from number of index position 0 in the right side and count up. The index number is power of 2

`int binary = 0b10010 -> #Ob43210 -> #0b(2^0+2^1+2^2+2^3+2^4) `

We have the calculation with the 2-based number system : 0 * (2^0)+ 1* (2^1)+ 0* (2^2)+ 0 * (2^3)+ 0 * (2^4) = 19








