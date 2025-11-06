# 🔍 Binary Search Visualizer

An **interactive web-based visualization tool** that demonstrates how the **Binary Search algorithm** works — step by step.  
Built using **HTML**, **CSS**, and **JavaScript**
---

## 🚀 Features

✅ **Dynamic Array Input** — Enter your own list of numbers (comma-separated).  
✅ **Auto Sorting** — Automatically sorts and removes duplicates.  
✅ **Interactive Modes**
- ▶️ **Auto Play** – Watch the algorithm run automatically.
- 🪜 **Step-by-Step Mode** – Click “Next Step” to manually walk through each iteration.
✅ **Pointers Visualization** – Clearly labeled pointers for **Left (L)**, **Mid (M)**, and **Right (R)**.  
✅ **Live Explanation Log** – See detailed messages describing each decision.  
✅ **Modern UI** – Smooth design and easy interaction with clean colors.  

---

## 🧠 How Binary Search Works

Binary Search is an algorithm used to efficiently find a target element in a **sorted array**.  
Instead of checking every element one by one, it cuts the array in half each time.

### Steps:
1. Start with two pointers — **left** (start) and **right** (end).
2. Calculate **mid = (left + right) / 2**.
3. Compare:
   - If `array[mid] == target` → 🎯 Found it!
   - If `array[mid] < target` → Move **left = mid + 1** (search right half).
   - If `array[mid] > target` → Move **right = mid - 1** (search left half).
4. Repeat until found or pointers cross.

📈 **Time Complexity:** `O(log n)`  
📦 **Space Complexity:** `O(1)`

---

## 🧩 Tech Stack

- **HTML5** – Page structure  
- **CSS3** – Styling, layout, transitions  
- **JavaScript (ES6)** – Algorithm logic & animations  
