# Common Char

Topic: `java, stringbuilder`

### Overview:

*   This program asks a user for two strings, and displays the number of common characters that the
two strings share.

### Step-by-step

*   Import the `Scanner` class from the `java.util` package.
    *   Create a Scanner object that reads from system input. 

```java
import java.util.Scanner;
public class commonChar {
	public static void main(String args[]) {
		Scanner read = new Scanner(System.in);
		// do something
	}
}
```

*   Prompt the user for two words.
    *   Assign `String` variables the user-given values.

```java
public static void main(String args[]) {
	Scanner read = new Scanner(System.in);
	System.out.print("Enter a word: ");
	String wordOne = read.nextLine();
	
	System.out.print("Enter another word: ");
	String wordTwo = read.nextLine();
	
}
```
