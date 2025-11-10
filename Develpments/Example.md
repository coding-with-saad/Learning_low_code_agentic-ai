# Example

Using a **Login System** example

---

### 💻 **Example Topic: Login System**

---

### 🤖 **1. AI-Driven Development**

In this method, we **ask AI to generate the code** for us.

**Step 1:**
Developer writes a simple prompt:

> “Create a login system with username and password validation.”

**Step 2:**
AI (like ChatGPT or GitHub Copilot) writes the code:

```python
username = input("Enter username: ")
password = input("Enter password: ")

if username == "admin" and password == "1234":
    print("Login successful!")
else:
    print("Invalid credentials!")
```

**Step 3:**
Developer tests and asks AI to improve it — maybe add encryption, database, or GUI.
AI updates the code automatically.

✅ **Result:**
Fast, smart, and adaptive. AI helps in every step.

---

### 📋 **2. Spec-Driven Development**

Here, we **start with a detailed plan (specification)** before writing code.

**Specification Document Example:**

1. The system should ask for username and password.
2. Username must not be empty.
3. Password must contain at least 8 characters.
4. If login is correct, print “Access Granted.”
5. If login fails, print “Access Denied.”

**Then, the developer writes code** according to these specs:

```python
username = input("Enter username: ")
password = input("Enter password: ")

if username == "" or len(password) < 8:
    print("Invalid input!")
elif username == "admin" and password == "12345678":
    print("Access Granted.")
else:
    print("Access Denied.")
```

✅ **Result:**
Code is reliable and exactly matches the written plan, but it takes more time to plan and write.

---

### 🔍 **Key Difference in the Example**

| Aspect                | AI-Driven Development               | Spec-Driven Development              |
| --------------------- | ----------------------------------- | ------------------------------------ |
| **Start Point**       | Natural language prompt             | Formal written document              |
| **Who creates logic** | AI generates logic                  | Developer follows the plan           |
| **Speed**             | Fast                                | Slower                               |
| **Flexibility**       | High — AI can change things quickly | Low — must follow spec strictly      |
| **Best for**          | Prototypes, experiments             | Large, rule-based, or secure systems |

---

### 💡 **In short**

* **AI-driven development** is like having a smart assistant write and improve your code.
* **Spec-driven development** is like building a house exactly from a blueprint — 
