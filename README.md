# XConsole-v1.0
This is an example of a console written in Java.
These are just test files and archive files for more information please message to clementmasiun@1998.gmail.com.

## Feature

### Version

* > __V1.0__

### Support

* > __Windows__ - _has been tested_
* > __Linux__ &emsp;&ensp; - not yet tested
* > __Mac__ &emsp;&emsp; - not yet tested

### Method

* #### Instance method
```java
public static Console console() 
```
* #### Print method
```java
public static void print(boolean b)
public static void print(char c)
public static void print(int i)
public static void print(long l)
public static void print(float f)
public static void print(double d)
public static void print(char s[])
public static void print(String s)
public static void print(Object obj)
```
* #### Println method
```java
public static void println()
public static void println(boolean b)
public static void println(char c)
public static void println(int i)
public static void println(long l)
public static void println(float f)
public static void println(double d)
public static void println(char s[])
public static void println(String s)
public static void println(Object obj)
```
* #### Error method
```java
public static void error(String msg)
```
* #### Next method
```java
public static String nextLine()
public static boolean nextBoolean()
public static char nextChar()
public static char[] nextChars()
public static int nextInt()
public static long nextLong()
public static float nextFloat()
public static double nextDouble()
public static short nextShort()
public static byte nextByte()
```
* #### Load File and Resource File Method
```java
public static File loadFile(String filename)
public static File getResourceFile(String filename)
public static URL getResource(String name)
```
* #### Property Method
```java
public static String getOSName()
public static String getOSType()
public static String getOSVersion()
```
* #### System Method
```java
public static void exit()
public static void pause(String ... prompt)
public static void sleep(long millis)
public static void clear()
```

## How to used

* #### Use on IntelliJ IDEA
Put the __Console.jar__ file on lib project.

Open Intellij IDE
>
> #### Open Project > File > Project Structure > Modules > Dependencies > Add > Select the Console.jar on lib > Click Ok

* #### Use with cmd
Create your project
>
> ###### Main.java
> xxDirectoryxx/xxProjectNamexx/test/Main.java<br>
> ###### Console.jar
> xxDirectoryxx/xxProjectNamexx/lib/Console.jar
Open command prompt and go to directory project
>
> #### > java -cp xxLibxx/Console.jar xxTestxx/Main.java
> or
> #### > java -classpath xxLibxx/Console.jar xxTestxx/Main.java
## Example

```java
package xconsole.test;
import xconsole.Console;
public class Main {
    public static void main(String[] args) {
	Console.clear();
        Console.println("This is simple Console library");
        Console.pause();
        Console.exit();
    }
}
```
