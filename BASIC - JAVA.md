
### Java Introduction:

1. **What is Java?**
      - Java is a high-level, object-oriented, platform-independent programming language.
      - It is used to build reliable, secure, and portable software applications.


      | 🔸 **Concept**                  | 🔹 **Summary / Purpose**                                     |
      |-------------------------------  |--------------------------------------------------------------|
      | **1) High-Level Language**     | Easy to read/write, uses English-like words                 |
      |                                | 📌 Makes programming human-friendly                          |
      | **2) OOPs (Object-Oriented)**  | Uses classes & objects, supports Encapsulation, etc.        |
      |                                | 📌 Helps in code reuse, organization, and security           |
      | **3) Platform Independent**    | Code runs on any OS (Windows, Linux, etc.)                  |
      |                                | 📌 *Write once, run anywhere* (done via JVM + bytecode)      |
      | **4) JVM (Java Virtual Machine)** | Runs `.class` bytecode on any system                     |
      |                                | 📌 Converts bytecode → machine code, adds portability        |
      | **5) Compiler (Java)**         | Reads full code at once, creates bytecode                   |
      |                                | 📌 Not like Python (line by line); prepares code for JVM     |

# 🔁 Java Architecture 

                              Start
                          ↓
                        Write Java Code (HelloWorld.java)
                          ↓
                        JDK (Java Development Kit)
                          ↓
                        ✔ Java Compiler compiles code
                          ↓
                        Bytecode is generated (.class file)
                          ↓
                        JRE (Java Runtime Environment)
                          ↓
                        ✔ JVM (Java Virtual Machine)
                             ↓
                           Executes Bytecode
                             ↓
                           Converts to Machine Code
                          ↓
                        Runs on Any OS (Windows, Linux, etc.)
                          ↓
                        Output Shown to User
                        End



---

## ✅ Java Components Explained

### **1️⃣ JDK – Java Development Kit**

🔹 Think of JDK as a **toolbox for developers**  
🔹 It includes:  
 ✔ Java Compiler (to convert code to bytecode)  
 ✔ JRE (to run the code)  
 ✔ Development tools  
📌 **Use:** If you're writing or developing Java programs, you need JDK.

---

### **2️⃣ JRE – Java Runtime Environment**

🔹 JRE is like a **player** that runs Java programs  
🔹 It includes:  
 ✔ JVM (to run the bytecode)  
 ✔ Core libraries  
📌 **Use:** If you're only running Java apps (not creating them), JRE is enough.

---

### **3️⃣ JVM – Java Virtual Machine**

🔹 JVM is the **heart of Java**  
🔹 It takes bytecode (compiled Java code) and **converts it into machine code**  
🔹 Makes Java **platform-independent**  
📌 **Use:** JVM lets the same Java program run on any OS (Windows, Linux, etc.)

---

