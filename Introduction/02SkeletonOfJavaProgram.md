# Skeleton of a Java Program

This Markdown explains the skeleton of a Java program and the meaning of every token.

---

## 📄 Java Program Skeleton

```java
public class MyFirst {
    public static void main(String[] args) {
        // Your code goes here
    }
}
```

---

## 🔹 Explanation of Each Token

1. **`public`**: Access modifier that allows the class or method to be accessible from anywhere.

2. **`class`**: Keyword used to declare a class in Java.

3. **`MyFirst`**: Name of the class. Class name should match the file name.

4. **`{ }`**: Curly braces define the start and end of a class or method block.

5. **`public static void main(String[] args)`**: This is the main method where program execution begins.

   * **`public`**: Access modifier, allows the JVM to call this method from anywhere.
   * **`static`**: Means the method can be called without creating an object of the class.
   * **`void`**: Specifies that the method does not return any value.
   * **`main`**: Name of the method. It's the entry point of any Java program.
   * **`String[] args`**: Parameter used to receive command-line arguments as an array of Strings.

6. **`// Your code goes here`**: Single-line comment explaining where to write program logic.

7. **`;`**: Semicolon denotes the end of a statement.

8. **`[ ]`**: Square brackets denote an array, here `String[]` is an array of Strings.

---

## 💻 How to Use Command Line to Run the Program

1. **Open Command Prompt** and navigate to the folder where your Java file is saved:

```cmd
cd C:\LearningJava
```

2. **Compile the Java Program**:

```cmd
javac MyFirst.java
```

* This generates `MyFirst.class` if there are no errors.

3. **Run the Compiled Program**:

```cmd
java MyFirst
```

* This executes the `main` method and prints any output to the console.

4. **Passing Command-Line Arguments** (Optional):

```cmd
java MyFirst arg1 arg2 arg3
```

* The arguments can be accessed inside the program using `String[] args`.

---

This structure is the **minimum required** for a Java program to compile and run.
