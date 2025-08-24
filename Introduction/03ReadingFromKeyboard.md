# Reading Input from Keyboard in Java

This Markdown explains how to read input from the keyboard in Java using the `Scanner` class.

---

## 📄 Program Example

```java
import java.util.Scanner;

public class KeyboardInput {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = sc.nextLine(); // Reads a line of text

        System.out.print("Enter your age: ");
        int age = sc.nextInt(); // Reads an integer

        System.out.println("Hello " + name + ", you are " + age + " years old.");

        sc.close(); // Close the Scanner
    }
}
```

---

## 🔹 Explanation of Key Parts

1. **`import java.util.Scanner;`**: Imports the Scanner class from the Java utility package.

2. **`Scanner sc = new Scanner(System.in);`**: Creates a Scanner object to read input from the keyboard.

3. **`sc.nextLine();`**: Reads a full line of text from the user.

4. **`sc.nextInt();`**: Reads an integer value from the user.

5. **`sc.close();`**: Closes the Scanner object to free system resources.

6. **`System.out.print`** vs **`System.out.println`**: `print` stays on the same line; `println` moves to the next line.

---

## 💻 Steps to Run the Program

1. Save the file as **`KeyboardInput.java`**
2. Open Command Prompt and navigate to the folder.

```cmd
cd C:\LearningJava
```

3. Compile the program:

```cmd
javac KeyboardInput.java
```

4. Run the program:

```cmd
java KeyboardInput
```

5. Enter input as prompted by the program.

---

## ✅ Sample Output

```
Enter your name: Sanket Kumar
Enter your age: 24
Hello Sanket, you are 24 years old.
```