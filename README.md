# 🚀 Daily LeetCode Problem Solving Journey

“I may not be the best coder today,
but I’ll be better than yesterday.” 🌱

This repo isn’t about perfection — it’s about growth, persistence, and consistency.

Welcome to my **LeetCode Daily Practice** repository!  
This repo is a collection of problems I solve daily to improve my **logic building**, **problem-solving**, and **coding skills**.  
It’s not fully optimized — but it’s all about **learning, consistency, and progress** 💪  

---


## 🌟 Why I Started
I believe the best way to grow as a programmer is through **daily problem-solving**.  
Each problem I solve helps me:
- Understand algorithms and data structures better  
- Learn new patterns and approaches  
- Improve logical thinking and clean code writing  
- Track my growth over time  

---

## 🧩 What’s Inside
Problems are categorized by difficulty and topic:
- 🟢 Easy — Strengthening the basics  
- 🟡 Medium — Building problem-solving patterns  
- 🔴 Hard — Exploring complex algorithmic logic  

---



## 📈 My Goals
📅 Solve at least one problem daily
🧠 Focus on logic over memorization
💻 Learn better coding patterns and time complexity optimization
🚀 Keep improving one line of code at a time

----

## 📊 Progress Tracker
Date	Problem	Difficulty	Topic	Language
| Date       | Problem           | Difficulty | Topic    | Language |
| ---------- | ----------------- | ---------- | -------- | -------- |
| 2025-10-15 | Two Sum           | Easy       | Hash Map | Python   |
| 2025-10-16 | Valid Parentheses | Easy       | Stack    | Python   |
| ...        | ...               | ...        | ...      | ...      |

---

## 🧰 Tools & Technologies
Languages: Python / C++ / Java
Platform: LeetCode
Editor: VS Code

---

## 📬 Connect with Me

If you’re also on a coding journey, let’s learn together!
Linkedin : www.linkedin.com/in/vijayseishiki

----

## 🗂️ Folder Structure
📂 LeetCode-Daily
┣ 📂 Easy
┣ 📂 Medium
┣ 📂 Hard
┣ 📜 README.md
┗ 📜 progress_log.md


Each folder contains:
- Problem link  
- My solution code (Python / C++ / Java)  
- Notes or key learnings  

---

## 🧠 Example Format
```python
# Problem: Two Sum
# Link: https://leetcode.com/problems/two-sum/
# Approach: Using Hash Map for quick lookup

class Solution:
    def twoSum(self, nums, target):
        seen = {}
        for i, num in enumerate(nums):
            if target - num in seen:
                return [seen[target - num], i]
            seen[num] = i


