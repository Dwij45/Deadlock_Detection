# 💻 Deadlock Detection Web Application using Banker's Algorithm

This project is a web-based system to simulate and detect potential **deadlocks in resource allocation** using the **Banker's Algorithm** — a classic method in operating systems to ensure system safety.

---

## 🚀 Features

- 🔍 Detects safe and unsafe states in resource allocation
- 💡 Interactive UI to input:
  - Available resources
  - Maximum need
  - Allocated resources
- 📊 Displays:
  - Need matrix
  - Safe sequence (if exists)
  - Deadlock warning (if unsafe)
- 🧠 Implements the **Banker's Algorithm** logic step-by-step

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: None (fully client-side logic)
- **Libraries/Tools**: Bootstrap (for styling), optional JS libraries for validation or UI

---

## 🧮 How It Works

1. User inputs the number of processes and resource types.
2. Provides:
   - Allocation Matrix
   - Maximum Demand Matrix
   - Available Resources
3. The app calculates:
   - Need = Max - Allocation
   - Checks if a **safe sequence** exists.
   - If not, reports **deadlock**.

