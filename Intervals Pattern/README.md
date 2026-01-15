## 📌 Intervals Pattern – Theory

📄 **Intervals_Pattern_Theory.pdf** contains the detailed explanation.

### 🔹 What is Intervals Pattern?
A pattern used to solve problems involving **ranges** and **overlapping intervals**.

### 🚀 When to use?
- Time/date ranges ⏱️
- Meeting scheduling 📅
- Booking systems 🏨
- Start–end pairs

### 🛠️ Core Idea
- Sort intervals by **start time**
- Merge if `current.start ≤ previous.end`

### ⏱️ Time Complexity
- Sorting: **O(n log n)**
- Traversal: **O(n)**
- Total: **O(n log n)**

### ⭐ Common Problems
- Merge Intervals
- Insert Interval
- Meeting Rooms
