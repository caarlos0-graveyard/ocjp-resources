# Question 1

```java
class MCZ11 {
  public static void main (String[] args) {
    char a = '\c';  // 1
    char b = '\r';  // 2
    char c = '\"';  // 3
    char d = '\b';  // 4
    char e = '\'';  // 5
}}
```

A compile-time error is generated at which line?

- a.  1
- b.  2
- c.  3
- d.  4
- e.  5
- f.  None of the above

# Question 2

```java
class GFM11{
  public static void main (String[] args) {
    int x,y,z;
    System.out.println(x+y+z);
}}
```

What is the result of attempting to compile and run the program?

- a.  Prints nothing.
- b.  Prints an undefined value.
- c.  Prints: null
- d.  Prints: 0
- e.  Run-time error
- f.  Compile-time error
- g.  None of the above

# Question 3

```java
class MCZ27 {
  public static void main (String[] args) {
    char a = '\f';  // 1
    char b = '\n';  // 2
    char c = '\r';  // 3
    char d = '\l';  // 4
    char e = '\\';  // 5
}}
```

A compile-time error is generated at which line?

- a.  1
- b.  2
- c.  3
- d.  4
- e.  5
- f.  None of the above

# Question 4

```java
class GRC4 {public static void main(String[] args) {}} // 1
class GRC5 {public static void main(String []args) {}} // 2
class GRC6 {public static void main(String args[]) {}} // 3
```

What is the result of attempting to compile and run the above programs?

- a.  Compile-time error at line 1.
- b.  Compile-time error at line 2.
- c.  Compile-time error at line 3.
- d.  An attempt to run GRC4 from the command line fails.
- e.  An attempt to run GRC5 from the command line fails.
- f.  An attempt to run GRC6 from the command line fails.
- g.  None of the above

# Question 5

```java
class MCZ28 {
  public static void main (String[] args) {
    char a = '\b';  // 1
    char b = '\d';  // 2
    char c = '\f';  // 3
    char d = '\t';  // 4
    char e = '\"';  // 5
}}
```

A compile-time error is generated at which line?

- a.  1
- b.  2
- c.  3
- d.  4
- e.  5
- f.  None of the above

# Question 6

```java
class JJF1 {
  public static void main (String args[]) {
    System.out.print(Byte.MIN_VALUE+",");
    System.out.print(Byte.MAX_VALUE);
}}
```

What is the result of attempting to compile and run the program?

- a.  Prints: 0,255
- b.  Prints: 0,256
- c.  Prints: -127,128
- d.  Prints: -128,127
- e.  Compile-time error
- f.  Run-time error
- g.  None of the above

# Question 7

```java
class GFC100 {
  public static void main(String[] args) {
    final short s1 = 1; // 1
    final char c1 = 1;  // 2
    byte b1 = s1;       // 3
    byte b2 = c1;       // 4
    byte b3 = 1;        // 5
    byte b4 = 1L;       // 6
    byte b5 = 1.0;      // 7
    byte b6 = 1.0d;     // 8
}}
```

Compile-time errors are generated at which lines?

- a.  1
- b.  2
- c.  3
- d.  4
- e.  5
- f.  6
- g.  7
- h.  8

# Question 8

```java
class MWC101 {
  public static void main(String[] args) {
    int[] a1 = new int[];              // 1
    int a2[] = new int[5];             // 2
    int[] a3 = new int[]{1,2};         // 3
    int []a4 = {1,2};                  // 4
    int[] a5 = new int[5]{1,2,3,4,5};  // 5
}}
```

Compile-time errors are generated at which lines?

- a.  1
- b.  2
- c.  3
- d.  4
- e.  5

# Question 9

```java
class GRC1 {public static void main(String[] args) {}}    // 1
class GRC2 {protected static void main(String[] args) {}} // 2
class GRC3 {private static void main(String[] args) {}}   // 3
```

What is the result of attempting to compile each of the three class declarations
and invoke each main method from the command line?

- a.  Compile-time error at line 1.
- b.  Compile-time error at line 2.
- c.  Compile-time error at line 3.
- d.  An attempt to run GRC1 from the command line fails.
- e.  An attempt to run GRC2 from the command line fails.
- f.  An attempt to run GRC3 from the command line fails.

# Question 10

```java
class JJF2 {
  public static void main (String args[]) {
    System.out.print(Short.MIN_VALUE+",");
    System.out.print(Short.MAX_VALUE);
}}
```

What is the result of attempting to compile and run the program?

- a.  Prints: -32767,32768
- b.  Prints: -32768,32767
- c.  Prints: 0,65535
- d.  Prints: 0,65536
- e.  Compile-time error
- f.  Run-time error
- g.  None of the above

# Question 11

```java
class GFC101 {
  public static void main(String[] args) {
    byte b1 = -128;    // 1
    byte b2 = 128;     // 2
    short s1 = -32769; // 3
    short s2 = 32767;  // 4
    char c1 = 0;       // 5
    char c2 = 65536;   // 6
}}
```

Compile-time errors are generated at which lines?

- a.  1
- b.  2
- c.  3
- d.  4
- e.  5
- f.  6

# Question 12

```java
class MWC102 {
  public static void main (String[] args) {
    byte[] a = new byte[1]; long[] b = new long[1];
    float[] c = new float[1]; Object[] d = new Object[1];
    System.out.print(a[0]+","+b[0]+","+c[0]+","+d[0]);
}}
```

What is the result of attempting to compile and run the program?

- a.  Prints: 0,0,0,null
- b.  Prints: 0,0,0.0,null
- c.  Compile-time error
- d.  Run-time error
- e.  None of the above

# Question 13

```java
class JJF3 {
  public static void main(String args[]) {
    System.out.print(Integer.toBinaryString(Byte.MAX_VALUE)+",");
    System.out.print(Integer.toOctalString(Byte.MAX_VALUE)+",");
    System.out.print(Integer.toString(Byte.MAX_VALUE)+",");
    System.out.print(Integer.toHexString(Byte.MAX_VALUE));
}}
```

What is the result of attempting to compile and run the program?

- a.  Prints: 1111111,177,127,7f
- b.  Prints: 11111111,377,256,ff
- c.  Compile-time error
- d.  Run-time error
- e.  None of the above

# Question 14

```java
class GFC102 {
  public static void main(String[] args) {
    byte b1 = -129;    // 1
    byte b2 = 127;     // 2
    short s1 = -32768; // 3
    short s2 = 32768;  // 4
    char c1 = -1;      // 5
    char c2 = 65535;   // 6
}}
```

Compile-time errors are generated at which lines?

- a.  1
- b.  2
- c.  3
- d.  4
- e.  5
- f.  6

# Question 15

Which of these words belong to the set of Java keywords?

- a.  transient
- b.  serializable
- c.  runnable
- d.  run
- e.  volatile
- f.  externalizable
- g.  cloneabl- e

# Question 16

```java
class GFM12 {
  static int x;                             // 1
  public static void main(String[] args) {  // 2
    int y;                                  // 3
    System.out.println("x="+x);             // 4
    System.out.println("y="+y);             // 5
}}
```

What is the result of attempting to compile and run the program?

- a.  Compile-time error at line 1.
- b.  Compile-time error at line 2.
- c.  Compile-time error at line 3.
- d.  Compile-time error at line 4.
- e.  Compile-time error at line 5.
- f.  Run-time error
- g.  None of the above

# Question 17

```java
class GFM13 {
  static byte a; static short b; static char c;
  static int d; static long e; static String s;
  public static void main(String[] args) {
    System.out.println(a+b+c+d+e+s);
}}
```

What is the result of attempting to compile and run the program?

- a.  Prints: 00000null
- b.  Prints: 00000
- c.  Prints: 0null
- d.  Prints: 0
- e.  Prints: null
- f.  Compile-time error
- g.  Run-time error
- h.  None of the above

# Question 18

Which of these words belong to the set of Java keywords?

- a.  virtual
- b.  goto
- c.  ifdef
- d.  typedef
- e.  friend
- f.  struct
- g.  implements
- h.  union
- i.  const

# Question 19

```java
class Identifiers {
  int i1;   // 1
  int _i2;  // 2
  int i_3;  // 3
  int #i4;  // 4
  int $i5;  // 5
  int %i6;  // 6
  int i$7;  // 7
  int 8i;   // 8
}
```

Compile-time errors are generated at which lines?


- a.  1
- b.  2
- c.  3
- d.  4
- e.  5
- f.  6
- g.  7
- h.  8
