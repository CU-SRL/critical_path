# Critical Path

A tool for engineering project managers to identify and manage critical path items in their projects.

## What is the Critical Path?

The **critical path** is the longest sequence of dependent tasks in a project that determines the minimum time needed to complete the project. Any delay to a task on the critical path directly delays the project's finish date — there is no scheduling slack for these tasks.

Tasks *not* on the critical path have **float** (also called slack): the amount of time they can be delayed without affecting the overall project timeline. Understanding which tasks have float and which do not allows project managers to prioritize effort, allocate resources strategically, and make informed trade-off decisions when schedules are at risk.

Critical path analysis is rooted in the **Critical Path Method (CPM)**, a project modeling technique developed in the late 1950s. CPM works by:

1. Listing all tasks required to complete the project
2. Identifying dependencies between tasks (what must finish before something else can start)
3. Estimating durations for each task
4. Calculating the **earliest** and **latest** start/finish times for every task
5. Identifying tasks where early start equals late start — these have zero float and form the critical path

## Why It Matters

Focusing on critical path items helps engineering teams:

- Identify which delays will actually slip the ship date
- Decide where to add resources to accelerate delivery
- Communicate risk clearly to stakeholders
- Avoid wasting effort optimizing tasks that won't affect the deadline
