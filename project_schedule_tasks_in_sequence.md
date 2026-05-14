# 📘 Study Notes: Putting Tasks in Sequence

## 🔹 1. Importance of Task Sequencing
- Building a schedule requires **arranging tasks in the correct order**
- Example analogy:
  - ✅ Cook dinner → Eat dinner
  - ❌ Eat dinner → Cook dinner
- Sequencing converts a **WBS (Work Breakdown Structure)** into a **project timeline**

---

## 🔹 2. Network Diagram
- A **network diagram** represents the sequence of tasks
- Key elements:
  - **Boxes (Nodes)** → Represent tasks
  - **Arrows (Links)** → Show relationships between tasks
- Can be created using:
  - Software tools
  - Sticky notes on a whiteboard

✅ Goal: Visualize task flow and order of execution

---

## 🔹 3. Task Dependencies
- A **task dependency** exists when one task affects the timing of another

### Key Roles:
- **Predecessor** → Task that controls timing
- **Successor** → Task being controlled

👉 Every task has:
- Start
- Finish

---

## 🔹 4. Types of Task Dependencies

### ✅ 4.1 Finish-to-Start (FS) — *Most Common*
- A task must **finish before the next task can start**

**Example:**
``` Text
[Analyze Current Process] → [Design New Process]

```
---

### ✅ 4.2 Finish-to-Finish (FF)
- A task must **finish before another task can finish**

**Example:**
```Text
[Development Complete] → [Testing Complete]

````
💡 Insight:
- If the first task is delayed, the second task’s **finish is also delayed**

---

### ✅ 4.3 Start-to-Start (SS)
- A task must **start before another task can start**

**Example:**
````Text
[Pour Concrete] → [Start Troweling]

````

⚠️ Risk:
- If the first task is delayed, the second task may produce incorrect results  
- Sometimes SS is mistakenly used when **FF is actually correct**

---

### ✅ 4.4 Start-to-Finish (SF) — *Rare*
- A task must **start before another task can finish**

**Example:**

[Second Shift Starts] → [First Shift Ends]

⚠️ Note:
- Rare and often confusing dependency type

---

## 🔹 5. Common Mistake Insight
- Using **Start-to-Start** when **Finish-to-Finish** is correct  
- Example:
  - Writing & Reviewing
  - If writing is delayed:
    - Reviewing may appear to finish early → ❌ Incorrect
  - Correct logic:
    - Both should finish together → ✅ Use FF

---

## 🔹 6. How to Identify the Correct Dependency

Ask these 3 questions:

1. **Which task controls the other?**
   - → Identifies the *predecessor*

2. **Does the start or finish of the first task control the second?**
   - → Determines first part (Start / Finish)

3. **Does it control the start or finish of the next task?**
   - → Determines second part (Start / Finish)

---

## 🔹 7. Outcome of Sequencing
- Adding dependencies to tasks creates:
  - A **logical sequence**
  - A **network diagram**
  - A **foundation for scheduling**

---

## 🔹 ✅ Key Takeaways
- Task sequencing is essential for creating a realistic schedule
- Dependencies define how tasks are linked
- Four dependency types: **FS, FF, SS, SF**
- Correct dependency selection avoids scheduling errors
- Network diagrams visualize and organize project workflows

---
