#  DFA Minimizer & Visualizer

A powerful web-based tool to **visualize and minimize Deterministic Finite Automata (DFA)** using:

-  Table Filling Algorithm (Myhill–Nerode)
-  Partition Refinement Algorithm (Hopcroft)
-  Step-by-step visualization
-  2D + 3D Graph View
-  String Simulator
-  Export (PNG & JSON)

---

#  What is DFA Minimization?

DFA Minimization is the process of reducing the number of states in a DFA **without changing the language it accepts**.

 It removes:
- Equivalent states
- Unreachable states

 Result:
- Smaller DFA
- Same behavior

---

#  How to Use (Step-by-Step)

##  Example Walkthrough

Let's take a simple DFA:

Input States: A,B,C,D

Alphabet: 0,1 

Start State: A

Final State: C,D

---

## Transition Table

| State | 0 | 1 |
|------|---|---|
| A    | B | C |
| B    | A | D |
| C    | D | C |
| D    | C | D |

---

#  Steps to Use Website

## Step 1️⃣ Enter DFA Details

- Fill **States**
- Fill **Alphabet**
- Enter **Start State**
- Enter **Final States**

 <img width="2780" height="421" alt="image" src="https://github.com/user-attachments/assets/885b524b-0625-47c9-b04a-ec971301743c" />


---

## 2️⃣ Click "Build Transition Table"

👉 Fill all transitions properly

---

## 3️⃣ Select Algorithm

Choose one:

- 🔵 Table Filling  
- 🟣 Partition Refinement  

---

## 4️⃣ Click "Minimize DFA"

👉 System will:

- Show step-by-step process
- Highlight state comparisons
- Build equivalence classes

---

## 5️⃣ View Result

👉 You will see:

- Original DFA
- Algorithm Visualization
- Minimized DFA

---

## 6️⃣ Use Step Controls

- ▶ Next Step
- ◀ Previous Step
- ⏯ Auto Play

---

## 7️⃣ 3D Visualization

👉 Click **"3D View"** to see minimized DFA in 3D

---

## 8️⃣ String Simulation

Test strings like:
