# Introduction to Java and JVM

This Markdown file explains Java installation, how Java programs are compiled, the role of JRE and JVM, and what happens behind the scenes when a Java program runs.

---

## 💻 Installing Java

1. Download and install the **Java Development Kit (JDK)** from the [official Oracle website](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Set the **JAVA\_HOME** environment variable to point to your JDK installation folder.
3. Add **`%JAVA_HOME%\bin`** to your system PATH variable.
4. Verify installation by opening Command Prompt and running:

```cmd
java -version
javac -version
```

---

## 🏃 How Java Programs Work

1. **Write Java Code**: You write your program in a `.java` file.
2. **Compilation**: Use the `javac` compiler to convert the `.java` file into bytecode (.class file).

```cmd
javac MyProgram.java
```

3. **Bytecode**: The `.class` file contains platform-independent bytecode, not machine code.
4. **Execution**: Run the program with the JVM.

```cmd
java MyProgram
```

---

## ⚙️ Java Runtime Environment (JRE)

* The **JRE** contains everything needed to run Java programs.
* It includes the **Java Virtual Machine (JVM)**, core libraries, and other supporting files.
* **JRE is only for running programs**, not for compiling them.

---

## 🖥️ Java Virtual Machine (JVM)

* The **JVM** is the engine that executes Java bytecode.
* It is platform-specific, meaning each OS has its own JVM implementation.
* Responsibilities of JVM:

  1. **Loading**: Loads `.class` files into memory.
  2. **Verifying**: Checks bytecode for security and correctness.
  3. **Executing**: Converts bytecode into machine code and runs it.
  4. **Memory Management**: Handles stack, heap, method area, and garbage collection.

---

## 📝 Compilation and Class File Creation

1. When you run `javac MyProgram.java`, the compiler:

   * Checks for syntax errors.
   * Converts your code into **bytecode**.
   * Creates a **`.class` file**.
2. The `.class` file is portable across different platforms that have a compatible JVM.

---

## ✅ Summary

* **JDK**: Needed to develop and compile Java programs.
* **JRE**: Needed to run Java programs.
* **JVM**: Executes bytecode, manages memory, and ensures platform independence.
* **.java file** → `javac` → **.class file** → `java` → JVM executes.

This gives a complete overview of how Java works under the hood from installation to execution.


