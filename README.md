# python-coding-interview-practice


This repository contains Python programs that solve common coding interview problems and real-world scenarios.
The goal of this repository is to improve **problem-solving skills, Python fundamentals, and logical thinking**.

Each problem is organized by difficulty level and focuses on different Python concepts such as **loops, lists, dictionaries, and sets**.

---

# 📌 Problem: IoT Sensor Network Analysis

## Problem Statement

In an IoT sensor network, the system stores a list of **registered sensor IDs** that are expected to send data.

During monitoring, the gateway receives a list of **active sensor IDs** that are currently transmitting data.

The task is to compare these lists and determine:

• **Working Sensors** – Sensors that are both registered and active.
• **Inactive Sensors** – Sensors that are registered but not sending data.
• **Unknown Sensors** – Sensors that are sending data but are not registered.

This helps detect **sensor failures or unauthorized devices in the network**.

---

# 🎯 Objective

Write a Python program that:

1. Accepts registered sensor IDs from the user
2. Accepts active sensor IDs from the user
3. Converts them into sets
4. Uses set operations to identify working, inactive, and unknown sensors

---

# 🧠 Concepts Used

* `input()` function
* `split()` for string processing
* `set()` data structure
* Set operations (`&`, `-`)

---


# ▶️ Example

Input

Registered IDs
110 102 105 108 104 107

Active IDs
110 108 105 104 112 222 412

Output

Working ID's are
{'104', '110', '105', '108'}

Inactive ID's are
{'107', '102'}

Unknown ID's are
{'222', '412', '112'}

---

# 🌍 Real-World Applications

This logic is used in:

• IoT sensor monitoring systems
• Device authentication systems
• Network security monitoring
• Access control systems
• Database comparison tools

---

# 👩‍💻 Author

Amrutha D N

