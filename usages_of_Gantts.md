# How to Create a Gantt Chart

## What a Gantt Chart Is
Step six of project management is creating the **Gantt chart**.  
A Gantt chart is a visual schedule that shows all project tasks as horizontal bars laid out over time.

- Tasks are listed vertically
- Time runs horizontally
- Bar lengths represent task duration

Because everything is drawn to scale, Gantt charts are easy to understand—even for people with no project management background.

The technique is named after **Henry Gantt**, who introduced it over a century ago.

---

## Always Start with Post‑it Planning
A Gantt chart should *never* be created first.

If you skip the Post‑it task sequencing step:
- Building the Gantt becomes slow and frustrating
- Dependencies will likely be wrong
- The critical path may be missed

The Post‑it diagram tells you:
- Task order
- Dependencies
- Which tasks are critical and which are floating

Once that exists, creating the Gantt chart is straightforward.

---

## Turning a Post‑it Plan into a Gantt Chart

### Step 1: Create the Basic Layout
- List tasks down the left side
  - Critical path tasks first
  - Floating tasks underneath
- Add time units (weeks or months) across the top

The total timeline length comes directly from the critical path duration.

---

### Step 2: Add the Critical Path
- Draw the critical tasks as a continuous stepped sequence
- Each task starts immediately after its predecessor
- Any intentional overlaps become instantly visible

This makes decisions—such as overlapping tasks to save time—clear and transparent.

---

### Step 3: Add Floating Tasks
Floating tasks are added one at a time.

For each task, ask:
1. What must this task start **after**?
2. What must it finish **before**?

These two dependencies define the task’s **float window**.

- Vertical markers show the earliest and latest possible positions
- The task bar can be placed anywhere within that range

---

## Two Important Float Patterns

### 1. Shared Float
Sometimes multiple tasks fit into the same available window.

Example:
- Hiring a manager
- Buying furniture

Both must be completed before installation, so they share the same float without conflict.

---

### 2. Floaters Depending on Floaters
Some tasks depend on tasks that are themselves movable.

Example:
- Hiring staff depends on hiring a manager
- The manager task can move
- The staff task “hangs” from it

Once you understand these two patterns, you can build Gantt charts of any size.

---

## Why Gantt Charts Are So Valuable

### 1. Communication
Gantt charts clearly show:
- Who is doing what
- When work happens
- How individual tasks fit into the whole project

They are far more intuitive than a simple task list.

---

### 2. Resource Planning
By scanning vertically, you can see:
- Busy weeks
- Quiet periods
- Potential overloads

This makes it possible to prepare for peak demand in advance.

---

### 3. Progress Tracking
Progress can be tracked by shading completed portions of tasks.

This allows you to compare:
- What *should* be finished by now
- What *is actually* finished

A plain checklist cannot show this comparison effectively.

---

### 4. Cost Control
Spending only makes sense alongside progress.

Example:
- 50% of the budget spent
- But only 25% of the work completed

A Gantt chart makes these mismatches visible and prevents false confidence.

---

# Creating a Gantt Chart in Excel

## Why Excel Works Well
Excel is ideal because:
- It is widely available
- It is quick to use
- It scales well, even for large projects

The principles described here apply to any project management software.

---

## Step‑by‑Step Excel Setup

### Step 1: Enter Tasks and Time Scale
- Tasks down the left-hand side
- Week numbers across the top
- Adjust column widths so the chart fits neatly

---

### Step 2: Use Conditional Formatting
Apply conditional formatting so that:
- Any cell greater than zero is automatically colored
- Different colors distinguish critical and floating tasks

This creates task bars without manual drawing.

---

### Step 3: Build the Critical Path
- Enter values (e.g. `1`) across the weeks where the task runs
- Copy and paste bars to adjust start dates
- Overlaps are easy to show by shifting bars sideways

---

### Step 4: Show Milestones
Tasks with zero duration (milestones) are shown as:
- A vertical line
- A diamond marker placed on that line

This clearly highlights key events such as “Go Live”.

---

## Adding Names and Real Dates

### Assign Task Owners
Insert a column to show:
- Who is responsible for each task

This improves accountability and commitment.

---

### Convert Weeks into Calendar Dates
- Enter a project start date
- Autofill weekly dates across the chart

This allows team members to:
- Check availability
- Plan diary commitments
- Confirm feasibility

---

## Adding Time and Cost Information

### Tracking Time and Effort
- Replace simple markers with hours or people per week
- Sum vertically to see weekly workload
- Sum horizontally to see total effort per task

This highlights:
- Peak workload periods
- Tasks that consume the most effort

---

### Tracking Costs
- Duplicate the Gantt sheet
- Replace hours with monetary values
- Analyze when and where money is spent

This enables cost sanity checks and early warnings.

---

## Scaling Up with Sub‑Gantts
For large projects:
- Keep the main Gantt high-level (around 20 tasks)
- Break complex tasks into sub‑Gantt charts on separate sheets

This keeps the main plan readable while allowing detailed control.

---

# Resource Planning for Multiple Projects

## The Challenge of Multiple Projects
In many organizations, **people** are the limiting factor—not money.

Without planning resources across projects:
- Teams become overloaded
- Schedules slip
- Strategic goals turn into wishlists

---

## The “Gantt of Gantts”
A combined view of all projects allows you to see:
- Which projects are complete
- Which are behind or ahead
- Which have not started as planned

It also helps answer key future questions:
- Can upcoming projects run in parallel?
- Do some need to be delayed?
- Are additional resources required?

---

## Why This Matters
A portfolio‑level Gantt:
- Improves decision‑making
- Enables realistic commitments
- Supports arguments for more staffing
- Aligns work with capacity

Despite its value, many organizations do not use one.

---

## Summary
Gantt charts:
- Translate planning into clarity
- Support communication, resources, progress, and costs
- Scale from single projects to full portfolios
- Are quick to build once Post‑it planning is complete

Always sequence with Post‑its first—then the Gantt chart becomes simple, powerful, and reliable.


# How to Create a Risk Chart

## Why Risk Planning Matters
All projects contain risk because they involve doing something new or unfamiliar.  
Step eight focuses on **anticipating problems before they happen**, reducing their impact, and clearly communicating any remaining exposure to stakeholders.

The objective is not to eliminate all risk — that is impossible — but to:
- Reduce risk as much as practical
- Make remaining risks visible and understood
- Allow informed decisions about whether to proceed

---

## Step 1: Identify Potential Risks
Start by listing everything that could realistically go wrong.

Common sources:
- Lessons learned from previous projects
- Input from experienced team members
- Brainstorming sessions
- External or environmental factors

At this stage, quantity matters more than precision.

---

## Step 2: Assess Likelihood and Impact
Each risk is evaluated along two dimensions:

- **Likelihood**: How likely is it to occur?
- **Impact**: How serious would the consequences be?

A simple scoring system works well:
- Scale both likelihood and impact from 1 to 5
- Multiply them to get an overall **risk score** (max 25)

This is not a perfect science, but it quickly highlights where attention is needed.

---

## Step 3: Decide Which Risks Matter
- High scores → Action required
- Low scores → Monitor only

The purpose of scoring is prioritization, not prediction.

---

## Step 4: Reduce Risk Where Possible
For each significant risk, aim to:
- Reduce the **likelihood**, or
- Reduce the **impact**, or
- Do both

Prevention is almost always better than reaction.

After mitigation actions are defined, reassess the scores to confirm that risk exposure has been reduced.

---

## Step 5: Communicate Residual Risk
Some risks cannot be eliminated.

These remaining risks should be:
- Documented
- Shared with stakeholders
- Accepted consciously

This protects the project team and allows stakeholders to make informed trade‑offs.

---

# How to Monitor Project Progress

## The Only Reliable Method
The most reliable way to know whether a project is on track is to **update the Gantt chart regularly**.

Track progress by:
- Coloring in completed portions of task bars
- Comparing progress against the moving **today line**

This provides an immediate visual truth of where the project stands.

---

## Why This Is Often Neglected
Many teams:
- Build a Gantt chart to get approval
- Never update it again

This wastes one of the most powerful project management tools.

---

## Why Visual Progress Tracking Works
A colored‑in Gantt chart shows:
- What has been completed
- What should have been completed by now
- Where delays are emerging

Stories and status reports explain activity — not progress.

---

## Regular Review Rhythm
- Short projects → weekly updates
- Long projects → monthly updates

For long tasks:
- Use sub‑Gantt charts to track partial completion
- Color in progress proportionally

If critical tasks start to lag, corrective action can begin early while recovery is still possible.

---

# Cost Monitoring: The Common Traps

## Why Cost Alone Is Misleading
Monitoring spending without considering progress is dangerous.

Example:
- Spending appears on track
- But little work has been completed

This can hide major problems until it is too late.

---

## Progress and Cost Must Be Compared
To interpret financial data correctly, you must know:
- How much work *should* be done
- How much work *has* been done
- How much that work *should have cost*

Only a Gantt chart provides this context.

---

## The Danger of Linear Assumptions
Accountants often assume costs are spread evenly over time.

Projects rarely behave this way:
- Early stages may be cheap
- Later stages may be expensive
- Or vice versa

Without planned spend profiles, overspends can remain invisible.

---

# The Six Combinations of Progress and Spend

When reviewing project performance, there are six common scenarios:

---

## 1. Overspent and Slightly Ahead
- Cost looks bad
- Progress softens the impact

Some overspend is explained by extra work completed.

---

## 2. Slightly Overspent but Well Ahead
- Looks like overspend
- Actually strong performance

Check quality and remaining expensive tasks — but often a good situation.

---

## 3. Overspent and Behind Schedule
- One of the worst scenarios
- Overspending is hidden by delay

Recovering time will usually increase costs further.

---

## 4. On Budget but Behind
- Looks perfect financially
- Actually late and overspent in value terms

Common in people‑only projects.

---

## 5. Heavy Early Overspend and Late
- Appears acceptable financially
- Actually critical risk

Often caused by expensive early tasks overrunning badly.

---

## 6. Slightly Behind but Underspent
- Some flexibility remains
- Extra funding can be used to recover time

Only scenario with room to maneuver.

---

## Key Lesson
Money numbers alone are meaningless without progress context.  
Always interpret costs through the Gantt chart.

---

# How to Forecast Final Cost and Completion Date

## Why Forecasting Matters
Knowing where you are today is useful — but knowing where you will end up is essential.

Forecasting requires judgment, not just arithmetic.

---

## The Critical Question
Are current problems:
- One‑off and resolved?
- Or structural and likely to continue?

Only the project manager can answer this.

---

## Simple Forecasting Approach

Example:
- Planned total cost: 100
- At halfway point:
  - Planned spend: 50
  - Actual spend: 55

Two possible outcomes:
- Problems resolved → finish at ~105
- Problems continue → finish at ~110

---

## General Rules
- If uncertainty exists → assume the trend continues
- If overspending early → expect further overspending
- If underspending early → likely to return to plan

Only assume recovery if the cause is clearly non‑repeatable.

---

## Same Logic for Time
The same logic applies to schedule forecasts:
- Early delays usually repeat
- Assume best only with strong evidence

Conservative forecasts protect trust and credibility.

---

## Summary
Effective control requires:
- Visual progress tracking
- Cost interpreted alongside schedule
- Honest forecasting
- Clear communication of remaining risk

The Gantt chart brings all these elements together into a single, reliable control tool.
``

# When to Re‑Adjust the Project Plan

## Why Re‑Planning Is Inevitable
Almost no project runs perfectly:
- Some tasks take longer than expected
- Costs drift upward
- Assumptions turn out to be wrong

Continuous monitoring tells you *what* is happening, but at some point you must decide **whether the remaining work can still be delivered under the original commitments**.

That decision is step 11 of the project lifecycle.

---

## The Key Question
The real question is not:
> “Can we still somehow save this?”

But rather:
> “Is it realistic to continue promising the original date and budget?”

Hope is not a strategy—and hope fades as the project progresses.

---

## The Best Timing: The Middle Third

A useful rule of thumb is to divide the project into three phases:

### First Third (0–33%)
Not the right time to re‑plan.

- Asking for more time or money too early looks like poor planning
- Reasonable delays should be absorbed and recovered internally
- The goal is to catch up quietly in subsequent tasks

> Exception:  
> If the **customer changes the scope**, ask for more time and money immediately and confirm it in writing.

---

### Middle Third (34–66%) ✅ *The Right Time*
This is the **optimal window** to re‑adjust the plan.

Why?
- Enough work has been done to see real trends
- There is still time to change course
- Stakeholders can realistically replan diaries and resources

If a nine‑month project is running late by month six, it is time to be honest.

---

### Final Third (67–100%)
Usually too late.

- Customers dislike last‑minute surprises
- Recovery options are limited
- Even if delays were partly the customer’s fault, blame often falls on the project manager

Waiting for a miracle late in the project usually makes the outcome worse.

---

## What Re‑Planning Involves
Re‑adjusting the plan may mean:
- Requesting a new completion date
- Requesting additional budget
- Reducing scope or quality
- Re‑sequencing remaining tasks

What matters most is **early, transparent communication**, not perfection.

---

## Rule of Thumb
Have the difficult conversation:
- Around the **halfway point**
- Certainly **before 70% completion**

Late honesty feels worse than early honesty—but it creates fewer problems.

---

# Why People Avoid Reviewing Projects

## The Importance of Project Reviews
The final step of project management is the **project review**.

A review:
- Captures lessons learned
- Improves future projects
- Recognizes effort and success
- Helps the organization grow

Despite this, reviews are often skipped.

---

## Seven Common Reasons Reviews Get Avoided

### 1. “There’s No Time”
Teams rush straight into the next project.

Ironically:
- A short review can save far more time later
- Skipping it guarantees repeated mistakes

---

### 2. “I Don’t Want to Relive the Pain”
Some projects are stressful or disappointing.

However:
- Avoiding reflection ensures the pain will return
- Learning reduces future frustration

---

### 3. “I Don’t Want to Admit Mistakes”
Fear of blame blocks learning.

Better approach:
- Keep reviews open and constructive
- Focus on *what happened*, not *who failed*
- Remove names from written learning points if needed

---

### 4. “It’s All in My Head”
Personal memory is unreliable.

- Details fade over time
- Insights remain locked with one person
- Written reviews share knowledge across the team

---

### 5. “It Went Fine, So No Review Is Needed”
Success is the **best time** to review.

Why?
- Successful techniques can be reused
- Good luck can be separated from good decisions
- Future projects can improve even further

---

### 6. “We’ll Never Do That Kind of Project Again”
In reality:
- Similar projects always return
- Other teams will face comparable challenges
- Lessons often apply more broadly than expected

---

### 7. “Nobody Will Read It”
This becomes true *only because* reviews are not habitually created.

Once a collection of reviews exists:
- It becomes a valuable reference
- People start consulting it naturally
- Organizational memory improves

---

## Making Reviews Work
Effective reviews should be:
- Short and focused
- Honest but non‑judgmental
- Stored centrally and accessibly
- Seen as part of the job, not an optional extra

They can even be enjoyable—people usually like sharing what they learned.

---

## Summary
Re‑adjusting the plan:
- Should happen in the **middle third**
- Requires honesty and courage
- Prevents larger failures later

Reviewing the project:
- Is the only way organizations learn
- Is avoided for understandable but flawed reasons
- Should always be done, especially after success

A project ends twice:  
Once when the work finishes—and once when the learning is captured.

