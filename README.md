# 💻 Banker's Algorithm - Deadlock Avoidance (C++)

This project simulates **Banker’s Algorithm** for *deadlock avoidance* using **C++**.  
It demonstrates how an operating system safely allocates resources among processes while preventing deadlocks.

---

## 🚀 Features
- Implements **Banker’s Safety Algorithm** to check if the system is in a safe state.  
- Implements **Resource Request Algorithm** to handle new requests from processes.  
- Demonstrates **two test cases**:
  1. **Safe State** – system remains safe after resource allocation.  
  2. **Unsafe State** – system becomes unsafe after request (request denied).  
- Displays all key matrices:
  - **Available**
  - **Allocation**
  - **Max**
  - **Need**
- Prints safe sequence if it exists.

---

## ⚙️ How It Works
1. Define number of processes (`n`) and resource types (`m`).
2. Initialize:
   - `Allocation[n][m]`
   - `Max[n][m]`
   - `Available[m]`
3. Compute `Need = Max - Allocation`.
4. Run **Safety Algorithm** to determine if system is safe.
5. Test **resource requests** using the **Request Algorithm**.

---

## 🧠 Learning Outcomes
- Gained hands-on experience implementing *deadlock avoidance* concepts.  
- Understood *safe and unsafe states* in OS resource allocation.  
- Strengthened *C++ matrix handling* and logical reasoning skills.  
- Practiced clean coding and algorithmic problem-solving.

---

## 🧩 Example Output
Allocation matrix:
0 1 0 0
2 0 0 1
1 1 1 0

Max matrix:
1 2 1 1
3 1 1 2
1 1 2 1

Need matrix (Max - Allocation):
1 1 1 1
1 1 1 1
0 0 1 1

Case A: Safe Sequence → P0 → P1 → P2
Case B: Unsafe (Request Denied)


---

## 📂 Files
| File | Description |
|------|--------------|
|  'Bankers-Algorithm-Deadlock-Avoidance'| Main source code implementing Banker’s algorithm |
| `README.md` | Project documentation |
| `output_screenshots/` | Example run screenshots |

---

## 🧰 Tech Stack
- Language: **C++ (GCC / g++)**
- IDE: **VS Code / Code::Blocks / Dev-C++**


🏁 Author

Manmeet Kaur
MCA | Tech Enthusiast | Exploring OS Concepts

📧 Feel free to connect on LinkedIn:
https://www.linkedin.com/in/manmeet-kaur-245a372ba/
🔖 Hashtags
#OperatingSystems #BankersAlgorithm #CPlusPlus #DeadlockAvoidance #MiniProject #ManmeetKaur
