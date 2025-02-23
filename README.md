I studied Crafting Interpreters in my 7th semester of college and wrote code for each chapter up to Chapter 10.

In the future, I plan to complete the book and reimplement the J-Lox interpreter from the book in another language, such as C#.

Additionally, I will complete the C-Lox compiler.

---

📖 **Crafting Interpreters: Summary (Up to Chapter 10)**  

### 🟢 Chapter 1: Introduction  
Introduces **interpreters vs. compilers** and explains why building an interpreter is valuable.  
Provides an overview of the **Lox programming language**, which you'll implement throughout the book.  

### 🟢 Chapter 2: A Tree-Walk Interpreter  
Implements a **basic interpreter for Lox** using a **recursive tree-walk approach**.  
Covers **tokens, expressions, and evaluating basic arithmetic**.  

### 🟢 Chapter 3: Scanning  
Introduces the **scanner (lexer)**, which converts raw source code into **tokens** (keywords, identifiers, literals, etc.).  
Implements a **stateful lexer** that reads characters and groups them into meaningful symbols.  

### 🟢 Chapter 4: Representing Code  
Introduces **Abstract Syntax Trees (ASTs)** to represent parsed expressions.  
Explains how **parsing expressions into tree structures** helps in evaluation.  

### 🟢 Chapter 5: Parsing Expressions  
Implements a **recursive descent parser** to convert tokens into an **AST**.  
Covers **operator precedence, grouping, and binary expressions**.  

### 🟢 Chapter 6: Evaluating Expressions  
Implements the **interpreter's evaluation step** using a **visitor pattern**.  
Supports **arithmetic, string concatenation, and boolean expressions**.  

### 🟢 Chapter 7: Statements and State  
Moves from **expressions to statements** (e.g., `print` and variable declarations).  
Introduces **variable storage using an environment (scope)**.  

### 🟢 Chapter 8: Control Flow  
Implements **if statements, while loops, and for loops**.  
Covers **logical operators (`and`, `or`)** and **short-circuiting behavior**.  

### 🟢 Chapter 9: Functions  
Adds **user-defined functions** and **function calls** to Lox.  
Covers **closures** (functions capturing variables from their outer scope).  

### 🟢 Chapter 10: Resolving and Binding  
Implements **static variable resolution** to track **which variable a name refers to**.  
Covers **lexical scoping** (resolving variables using block scope rules).  

---

### 🛠️ **Key Takeaways from Chapters 1-10**  
✅ You build a fully functional **tree-walk interpreter** for Lox.  
✅ You understand **lexing, parsing, evaluation, and control flow**.  
✅ You implement **functions, variable scopes, and closures**.  
✅ You prepare for the next step: **optimizing the interpreter and adding advanced features**.  

---

## 📚 **Resources**  
- 📘 **Official Book Website**: [Crafting Interpreters](https://craftinginterpreters.com/)  
