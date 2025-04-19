# 💼 Income & Expense Tracker

## 🎯 Objective
Build a fully functional **Income & Expense Tracker** using JavaScript. You are provided with the HTML structure and CSS styling (light theme). Your task is to create a JavaScript module (`script.js`) that makes the page dynamic and interactive.

---

## 📋 Requirements

### ✅ 1. Form Submission
- Capture input fields: `description`, `amount`, `date`, and `type` (income or expense).
- Validate the inputs:
  - No field should be empty.
  - `amount` must be a valid number.
- On successful validation:
  - Add the new entry to the entry list.
  - Update the summary totals.
  - Reset the form.

### ✅ 2. Entry Display
- Display entries in the **Entries Section** with correct styles:
  - Use `.income` and `.expense` classes to apply proper coloring.
- Each entry must show:
  - Description
  - Amount (prefix with `+` or `–` depending on type)
  - Date (optional enhancement)

### ✅ 3. Summary Totals
- Maintain running totals for:
  - Total income
  - Total expenses
  - Net balance (income - expense)

### ✅ 4. Filter Entries by Date
- Use the two date filter inputs to limit displayed entries.
- Only show entries that fall within the selected date range.
- If filters are empty, show all entries.

---

## 💡 Bonus Challenges
- [ ] Store and retrieve entries using `localStorage`.
- [ ] Enable deletion of individual entries.
- [ ] Add entry animations (on add/remove).

---

## 📂 Project Structure

```
📁 income-expense-tracker/
├── index.html        // Already provided
├── style.css         // Already styled with light theme
└── script.js         // 🔧 Your task is to build this
```

---

## 🎓 Learning Outcomes
- Master DOM manipulation
- Understand form handling and validation in JavaScript
- Learn date filtering and array management
- Write modular and clean JS code

---

Happy Coding! 🚀

