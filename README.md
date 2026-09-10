# ==========================================
# 💰 SMART EXPENSE TRACKER APPLICATION README
# 👨‍💻 Created By : Shukla Arpit
# ==========================================

import os
import time

# Clear Screen
def clear():
    os.system("cls" if os.name == "nt" else "clear")

# Animated Title
frames = [
"""
💰💰💰💰💰💰💰💰💰💰💰💰💰💰💰💰

      SMART EXPENSE TRACKER

💰💰💰💰💰💰💰💰💰💰💰💰💰💰💰💰
""",
"""
📊📊📊📊📊📊📊📊📊📊📊📊📊📊📊📊

      SMART EXPENSE TRACKER

📊📊📊📊📊📊📊📊📊📊📊📊📊📊📊📊
""",
"""
💸💸💸💸💸💸💸💸💸💸💸💸💸💸💸💸

      SMART EXPENSE TRACKER

💸💸💸💸💸💸💸💸💸💸💸💸💸💸💸💸
"""
]

for i in range(3):
    for f in frames:
        clear()
        print(f)
        time.sleep(0.4)

clear()

# Expense Logo (ASCII Image)
print("""
                💰
          ╔══════════════╗
          ║   💵 WALLET  ║
          ╚══════════════╝

         📈📉📊 Expense Tracker 📊📉📈
""")

time.sleep(1)

# Loading Animation
print("\nLoading Smart Expense Tracker...\n")
for i in range(0, 101, 5):
    bar = "█" * (i // 5) + "░" * (20 - i // 5)
    print(f"\r[{bar}] {i}%", end="")
    time.sleep(0.08)

print("\n\n✅ Project Loaded Successfully!\n")
time.sleep(1)

# README Content Animation
readme = """
╔════════════════════════════════════════════════════════════╗
║      🚀 SMART EXPENSE TRACKER APPLICATION 🚀              ║
╚════════════════════════════════════════════════════════════╝

👨‍💻 Developer : Shukla Arpit
🐍 Language  : Python

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 PROJECT DESCRIPTION

Smart Expense Tracker is a Python application that helps
users manage, save, analyze and visualize daily expenses.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✨ FEATURES

✔ Add Expense
✔ View Expense Summary
✔ Filter Expenses
✔ Generate Expense Report
✔ Save Expenses in CSV File
✔ Category-wise Analysis
✔ Beautiful Data Visualization

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🛠 MODULES USED

🐍 Python
📊 Pandas
🔢 NumPy
📈 Matplotlib
🎨 Seaborn
📄 CSV

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📊 VISUALIZATIONS

📊 Bar Chart
📈 Line Graph
🥧 Pie Chart
📉 Histogram

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🎯 PROJECT OBJECTIVE

• Track Daily Expenses
• Analyze Spending Habits
• Store Data Securely in CSV
• Display Reports with Graphs

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📂 PROJECT FILES

📁 expense_tracker.py
📄 expenses.csv
📘 README.py

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
"""

for line in readme.split("\n"):
    print(line)
    time.sleep(0.05)

# Thank You Animation
thanks = [
    "💖 THANK YOU FOR USING SMART EXPENSE TRACKER 💖",
    "🌟 KEEP LEARNING PYTHON 🌟",
    "🚀 KEEP BUILDING AMAZING PROJECTS 🚀"
]

for text in thanks:
    print("\n" + text)
    time.sleep(0.8)

print("\n✨ README COMPLETED SUCCESSFULLY ✨")# SMART-EXPENSE-TRACKER-APPLICATION
💰 SMART EXPENSE TRACKER 💰
[████████████████████] 100%

👨‍💻 Developer : Shukla Arpit
🐍 Language : Python

✨ FEATURES
✔ Add Expense
✔ View Summary
✔ Filter Expenses
✔ Generate Report
✔ CSV Storage
✔ Graph Visualization

💖 THANK YOU FOR USING SMART EXPENSE TRACKER 💖
🚀 KEEP BUILDING AMAZING PROJECTS 🚀
