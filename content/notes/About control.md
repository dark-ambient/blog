#### 5 types of control
1. At the end, right before a deadline. High confidence a person can and will do the task. Also, small tasks are good candidates for that.
2. Preliminary
3. Each milestone
4. Periodic. Every N units of time (every day, week, month). Depends on a task
5. Selective, Random; when there are too many (conveyor, a random bottle is open for a check)

#### Charts

**1. At the end**
```mermaid
flowchart LR
Start-->Work-->Check(🔍)-->Deadline
```

**2. Preliminary**
```mermaid
flowchart LR
Start-->Check(🔍)-->Work-->Deadline
```

**3. Each milestone**
```mermaid
flowchart LR
Start-->M1(🔍)-->M2(🔍)-->M3(🔍)-->Deadline
```

**4. Periodic**
```mermaid
flowchart LR
Start-->Day1(🔍)-->Day2(🔍)-->Day3(🔍)-->Deadline
```

**5. Selective, Random**
```mermaid
flowchart LR
T1(task)-->Done
T2(task)-->Check(🔍)
T3(task)-->Done2(Done)
T4(task)-->Done3(Done)
```
