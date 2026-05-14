# 📘 Study Notes: Using Milestones in Project Scheduling

## 🔹 1. What Are Milestones?
- Milestones come from historical road markers placed at intervals (e.g., miles)
- In projects, they represent **key events or achievements**
- Used to track **progress and important points**, not distance

---

## 🔹 2. Purpose of Milestones
- Show:
  - ✅ What has been completed
  - ✅ When it was completed
- Help measure overall **project progress**
- Provide clear **checkpoints**

---

## 🔹 3. Key Characteristics
- **Zero duration** (no time required)
- Represent **events, not tasks**
- Used for **tracking and control**

---

## 🔹 4. Where to Use Milestones

### ✅ 4.1 Project Start & End
- **Start Milestone**
  - Makes it easy to shift the entire schedule
- **End Milestone**
  - Indicates if the project is:
    - On time
    - Late
    - Ahead of schedule

---

### ✅ 4.2 Progress Tracking
- Place between major phases
- Helps track completion of chunks of work

Example:
    [Phase 1 Complete] → [Phase 2 Complete]

---

### ✅ 4.3 Deliverables
- Use to mark deliveries from vendors or teams

Example:
    [Delivery Received]

---

### ✅ 4.4 Decisions & Approvals
- Highlight critical decision points
- Control when future work can begin

Examples:
    [Design Approved]
    [Go/No-Go Decision]

---

## 🔹 5. Linking Milestones
- Milestones are connected to tasks using dependencies
- When linked:
  - They mark completion of preceding work
  - They help adjust the schedule dynamically

---

## 🔹 6. Benefits of Milestones
- ✅ Clear visibility of progress
- ✅ Easy tracking of key events
- ✅ Improved communication with stakeholders
- ✅ Simplifies schedule adjustments

---

## 🔹 7. Example Flow

    [Project Start]
            ↓
    [Planning Tasks]
            ↓
    [Planning Complete ✅] (Milestone)
            ↓
    [Execution Tasks]
            ↓
    [Execution Complete ✅] (Milestone)
            ↓
    [Project Finish ✅] (Milestone)

---

## 🔹 ✅ Key Takeaways
- Milestones mark **important events**, not work
- They have **no duration**
- Common uses:
  - Start and end points
  - Progress checkpoints
  - Deliveries
  - Approvals
- Linking milestones improves schedule control

---

# 📘 Study Notes: Making a Realistic Project Schedule

## 🔹 1. Importance of a Realistic Schedule
- A schedule should reflect **real working conditions**
- Goal:
  - Ensure tasks occur **close to planned dates**
- Unrealistic schedules lead to:
  - Delays
  - Resource overload
  - Missed deadlines

---

## 🔹 2. Consider Actual Working Time

### ✅ Key Insight:
- People do **NOT work 100% of their time on tasks**

### Time lost due to:
- Meetings
- Administrative work (paperwork)
- Training
- Breaks / Time off
- Moving between locations (e.g., walking across campus)

👉 Always estimate **actual productive hours**, not total work hours

---

## 🔹 3. Adjust for Resource Productivity

- Not all team members work at the same speed

### Example:
- A highly skilled worker may:
  - Complete tasks faster
  - Reduce required work hours

✅ Action:
- Adjust **task effort (hours)** based on:
  - Skill level
  - Experience
  - Efficiency

---

## 🔹 4. Limit Multitasking

### ✅ Best Practice:
- Assign resources to **maximum 3 tasks at a time**

### Why?
- Task switching causes:
  - Loss of focus
  - Small delays each time
  - Reduced productivity

---

## 🔹 5. Adjust for Resource Overload

- If a resource must handle multiple tasks:

### 👉 Apply adjustments:
- Increase task duration
- Reduce productivity assumptions

✅ Reason:
- More tasks = less efficiency per task

---

## 🔹 6. Document Your Adjustments

- Always add **notes to the schedule** when:
  - You adjust durations
  - You modify resource assignments

### Include:
- What was changed
- Why it was changed

✅ Benefit:
- Helps with:
  - Future planning
  - Managing further changes

---

## 🔹 7. Outcome of Realistic Scheduling
- Better alignment with reality
- Improved ability to:
  - Stay on schedule
  - Manage resources effectively
  - Predict delays early

---

## 🔹 ✅ Key Takeaways
- People don’t work 100% of the time on tasks
- Account for real-world interruptions
- Adjust estimates based on individual productivity
- Limit multitasking to maintain efficiency
- Document all scheduling changes for future reference
- Realistic planning improves project success

---

# 📘 Study Notes: Understanding the Critical Path

## 🔹 1. What Is the Critical Path?
- The **critical path** is the **longest sequence of dependent tasks** in a project schedule
- It determines the **minimum time required to complete the project**

✅ Key Rule:
- Any delay in a critical path task → delays the **entire project**

---

## 🔹 2. Why Is It Important?
- Helps identify:
  - Tasks that **must stay on schedule**
- Enables:
  - **On-time delivery**
  - Opportunities to **shorten project duration**

✅ Insight:
- Shorten the critical path → shorten the **overall project timeline**

---

## 🔹 3. Critical Path vs Non-Critical Tasks

### ✅ Critical Tasks:
- Have **zero slack (float)**
- Cannot be delayed without affecting the project end date

### ✅ Non-Critical Tasks:
- Have **slack (float)**
- Can be delayed without impacting the overall schedule

---

## 🔹 4. What Is Slack (Float)?
- **Slack (or float)** = amount of time a task can be delayed **without delaying the project**

### Example:
- Task with 2 weeks slack:
  - Can start later without impacting project finish date

---

## 🔹 5. Early and Late Dates

Each task has **two sets of dates**:

### ✅ Early Dates (Forward Pass)
- **Early Start (ES)** → Earliest possible start
- **Early Finish (EF)** → Earliest possible finish

👉 Calculated by:
- Moving **forward** from project start
- Using task durations and dependencies

---

### ✅ Late Dates (Backward Pass)
- **Late Start (LS)** → Latest start without delay
- **Late Finish (LF)** → Latest finish without delay

👉 Calculated by:
- Moving **backward** from project end

---

## 🔹 6. How to Identify Slack

### Formula:
    Slack = Late Start - Early Start
    (or)
    Slack = Late Finish - Early Finish

---

## 🔹 7. Identifying Critical Path Tasks

✅ A task is **critical if**:
    Early Start = Late Start
    Early Finish = Late Finish

👉 This means:
- **No flexibility (zero slack)**

---

## 🔹 8. Example Insight

### Critical Task:
    Training Task
    ES = LS
    EF = LF
→ No slack → On critical path

### Non-Critical Task:
    Reports Task
    ES = Oct 26
    EF = Nov 27
    LS = Nov 16
    LF = Dec 18

→ Has slack → Not on critical path

---

## 🔹 9. Key Observations
- Tasks on the critical path:
  - Must be closely monitored
- Tasks with slack:
  - Provide scheduling flexibility

---

## 🔹 10. Tools and Automation
- Project scheduling tools:
  - Automatically calculate:
    - Critical path
    - Early/late dates
    - Slack

✅ No need for manual calculations in most real projects

---

## 🔹 ✅ Key Takeaways
- Critical path = **longest path through project**
- Determines **project duration**
- Tasks on it have **zero slack**
- Delays = direct impact on project finish date
- Focus on critical path to:
  - Keep project on track
  - Optimize schedule

---
# 📘 Study Notes: How to Shorten a Project Schedule

## 🔹 1. Why Shorten a Schedule?
- Stakeholders often ask for:
  - ✅ Earlier delivery
  - ✅ Recovery from delays
- Goal: **Reduce total project duration**

---

## 🔹 2. Key Principle
- Focus on the **critical path**
- Only shortening tasks on the **critical path** will:
  - ✅ Reduce overall project duration

---

## 🔹 3. Techniques to Shorten a Schedule

## ✅ 3.1 Fast Tracking
- **Definition:**
  - Overlap tasks that were originally sequential

### Example:
- Start software design **before system design is fully completed**

### How it works:
- Modify **Finish-to-Start (FS)** dependencies
- Introduce **overlap**

### Best Use:
- Long tasks on the **critical path**

### ✅ Advantages:
- No additional cost
- Faster schedule reduction

### ⚠️ Disadvantages:
- Increased **risk**
- Possible **rework**

**Example Risk:**
- Changes in system design → rework in software design

---

## ✅ 3.2 Crashing
- **Definition:**
  - Add **extra resources or cost** to finish tasks faster

### Methods:
- Add more people
- Pay for expedited materials
- Use better tools or technology

### Focus:
- Only crash tasks on the **critical path**

---

### 💰 Cost Optimization Strategy
1. Start with **lowest cost tasks**
2. Use a **crash table**:
   - Shows:
     - Cost to crash
     - Time saved
3. Select tasks with:
   - Lowest **cost per time saved**

---

### ✅ Rules for Crashing:
- Crash only until:
  - Required time reduction is achieved
- Prefer:
  - Tasks with **lower cost per week saved**
- If equal cost:
  - Crash **longer tasks first**

---

### ⚠️ Limits of Crashing:
- Too many people can reduce efficiency:
  - Team congestion
  - Communication overhead
- New resources require:
  - Training and onboarding
- May slow down existing team members

---

## ✅ 3.3 Reducing Scope
- **Definition:**
  - Remove or reduce project deliverables

### Impact:
- If removed tasks are on the **critical path**:
  - ✅ Schedule shortens

### Trade-off:
- Reduced project scope = reduced output/value

---

## 🔹 4. Re-evaluate After Changes
- Always **recalculate the critical path** after any change

### Why?
- Changes can:
  - Shift the critical path
  - Make new tasks critical

---

## 🔹 5. Comparison of Techniques

| Technique        | Cost Impact | Risk Level | Effectiveness |
|-----------------|------------|-----------|--------------|
| Fast Tracking   | Low        | High      | Medium       |
| Crashing        | High       | Medium    | High         |
| Scope Reduction | Low–Medium | Low       | High         |

---

## 🔹 ✅ Key Takeaways
- Always focus on the **critical path**
- **Fast tracking** = overlap tasks → faster but risky
- **Crashing** = add resources → faster but costly
- **Scope reduction** = remove work → fastest but reduces value
- Recalculate critical path after every adjustment
- Choose method based on:
  - Cost
  - Risk
  - Project priorities

---
# 📘 Study Notes: Documenting the Project Baseline

## 🔹 1. What Is a Project Baseline?
- A **project baseline** is the collection of:
  - ✅ Approved project documents
- It represents the **original plan** against which performance is measured

### Includes:
- Requirements
- Schedule
- Budget
- Supporting documents (spreadsheets, plans, etc.)

---

## 🔹 2. Purpose of the Baseline
- Used to:
  - Compare **actual performance vs planned performance**
- Helps answer:
  - Are we on track?
  - Are we ahead or behind?

---

## 🔹 3. Role in Change Management
- The baseline is controlled by the **Change Management Process**

### Key Rule:
- Any modification to baseline documents:
  → Becomes a **change request**

✅ Ensures:
- Controlled and traceable changes
- No uncontrolled updates

---

## 🔹 4. How to Define the Baseline

### ✅ Step 1: Save Baseline Versions of Documents
- Store approved versions of:
  - Project plan
  - Requirements
  - Budget
  - Other key documents

### When changes occur:
- Create a **new revision**
- Clearly **flag what changed**

---

### ✅ Step 2: Baseline the Project Schedule
- Use scheduling software features to:
  - Save **baseline values**

### Baseline schedule includes:
- Start dates
- Finish dates
- Task durations
- Work estimates
- Costs

---

### ✅ Step 3: Track Variance
- As project progresses:
  - Record actual performance
- Tools will show:
  - Difference between:
    - Baseline vs Actual (variance)

---

## 🔹 5. Why Baselines Are Important
- Provide a **reference point** for measuring success
- Help identify:
  - Delays
  - Cost overruns
  - Performance issues

---

## 🔹 6. Example Concept

Baseline:
    Task A → Start: Jan 1 | Finish: Jan 5

Actual:
    Task A → Start: Jan 2 | Finish: Jan 7

→ Variance:
    +1 day delay start
    +2 days delay finish

---

## 🔹 7. Best Practices
- Store baseline documents in:
  - Central repository (e.g., SharePoint, project folder)
- Ensure:
  - Easy access
  - Version control
- Clearly label:
  - Baseline vs revised versions

---

## 🔹 ✅ Key Takeaways
- Baseline = **approved version of project documents**
- Used to measure **project performance**
- Changes require **formal approval (change request)**
- Includes both:
  - Documents
  - Schedule data
- Essential for tracking progress and managing changes effectively

---
# 📘 Study Notes: Challenge – Creating a Network Diagram

## 🔹 1. Objective of the Challenge
- Develop a **network diagram** for a given project scenario
- Goal:
  - **Sequence tasks efficiently**
  - **Minimize total project duration**

---

## 🔹 2. Scenario Context
- Project expansion:
  - Add functionality to **track and manage hospital procedure costs**
- You are given:
  - A list of tasks (from exercise files)
- Your job:
  - Arrange them logically into a **network diagram**

---

## 🔹 3. Key Steps to Build the Network Diagram

### ✅ Step 1: Identify All Tasks
- Extract tasks from the WBS
- Ensure each task is:
  - Clearly defined
  - Has a start and finish

---

### ✅ Step 2: Determine Dependencies
For each task, identify:
- **Predecessor** (what comes before)
- **Successor** (what comes after)

👉 Ask:
- What must happen before this task begins?
- Can any tasks run in parallel?

---

### ✅ Step 3: Choose Dependency Types
Use:
- **FS (Finish-to-Start)** → Most common
- **SS (Start-to-Start)** → For parallel work
- **FF (Finish-to-Finish)** → For synchronized completion
- **SF (Start-to-Finish)** → Rare

---

### ✅ Step 4: Arrange Tasks for Efficiency
- Try to:
  - Run tasks **in parallel where possible**
  - Avoid unnecessary delays
- Focus on:
  - Reducing the **critical path length**

---

### ✅ Step 5: Draw the Network Diagram

Structure like:

    [Task A] → [Task B] → [Task C]
          ↘
           → [Task D]

- Boxes → Tasks
- Arrows → Dependencies

---

## 🔹 4. Optimization Tips

### ✅ Minimize Project Duration
- Overlap tasks where feasible (parallel work)
- Avoid strict sequencing unless required

---

### ✅ Focus on Critical Path
- Longest sequence determines duration
- Optimize this path first

---

### ✅ Avoid Common Mistakes
- Incorrect dependency types
- Missing dependencies
- Over-sequencing tasks unnecessarily

---

## 🔹 5. Validation Checklist
Before finalizing your diagram:

- [ ] All tasks are included  
- [ ] Dependencies are logical  
- [ ] No task starts before required inputs  
- [ ] Parallel work is maximized where possible  
- [ ] Critical path is minimized  

---

## 🔹 6. Learning Outcome
- Understand how to:
  - Convert task lists into **logical sequences**
  - Build **efficient project schedules**
  - Identify opportunities to **save time**

---

## 🔹 ✅ Key Takeaways
- Network diagrams visualize **task flow and dependencies**
- Efficient sequencing reduces project duration
- Parallel execution is key to optimization
- Critical path determines overall schedule length

---
