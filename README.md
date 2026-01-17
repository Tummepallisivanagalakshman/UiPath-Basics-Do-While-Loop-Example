# UiPath Basics – Do While Loop Example

## 📌 Project Overview
This project demonstrates the use of the **Do While** loop in UiPath.  
It is designed for beginners to understand how a Do While loop works and how it differs from a While loop.

---

## 🎯 Objective
- Learn how the **Do While** loop works in UiPath  
- Understand condition checking after execution  
- Control loop execution using a counter variable  

---

## 🧩 Workflow Description
1. An integer variable named `counter` is initialized with the value `1`.
2. A **Do While** activity is used with the condition `counter <= 3`.
3. Inside the loop:
   - A message box displays the current value of the counter.
   - The counter is incremented by 1.
4. The loop continues until the condition becomes false.

---

## 🛠️ Tools & Technologies
- UiPath Studio
- Control Flow Activities
- Do While Loop
- Assign Activity
- Message Box

---

## 📂 Variables Used
| Variable Name | Type  | Description                    |
|--------------|-------|--------------------------------|
| counter      | Int32 | Controls the loop execution    |

---
Count is: 1
Count is: 2
Count is: 3

---

## 📘 Learning Outcomes
- Understanding **Do While loop behavior**
- Knowing when to use Do While instead of While
- Importance of updating loop variables
- Avoiding infinite loops

---

## 🔍 While vs Do While (Quick Note)
- **While** → Condition checked before execution  
- **Do While** → Executes at least once, then checks condition  

---

## 👤 Author
**Tummepalli Sivanagalakshman**

---

## 🚀 Next Enhancements
- Compare Do While with While loop
- Replace Message Box with Log Message
- Use Do While for retry-based automation

---

## 📎 Notes
This project is created for **learning and practice purposes** and is suitable for UiPath beginners.


## ▶️ Expected Output
When the workflow runs, message boxes appear in this order:
