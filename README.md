# Personal Expense Tracker

## Description
The **Personal Expense Tracker** is a SwiftUI application that allows users to manage their daily expenses efficiently. Users can add new expenses, categorize them, view the expenses in a dynamic list, sort them by amount, and filter them by category. Additionally, the app provides a **dark mode toggle** for a better user experience.

## Features
✅ Add an expense with **name, amount, and category**
✅ View a dynamically updated **list of expenses**
✅ Sort expenses by **amount (ascending/descending)**
✅ Filter expenses based on **category**
✅ Enable/disable **dark mode** for a customizable theme

## How It Works
### 1️⃣ Adding an Expense
- Tap on the **Add** button in the toolbar.
- Enter an **expense name**.
- Enter the **amount** (numeric input only).
- Select a **category** (Food, Travel, Shopping).
- Press **Add** to save the expense.

### 2️⃣ Viewing Expenses
- Expenses are displayed in a **dynamic list**.
- Each expense shows its **name, amount (formatted in currency), and category**.
- Expenses update in real time when added.

### 3️⃣ Sorting & Filtering
- Use the **Sort by Amount** button to toggle between **ascending and descending order**.
- Use the **category filter** to display only expenses from a specific category.

### 4️⃣ Dark Mode
- Toggle the **Dark Mode** switch to change between **light and dark themes**.

## Technologies Used
- **SwiftUI** for UI design
- **State Management** with `@State`, `@ObservedObject`, and `@Published`
- **List & Picker Components** for displaying and filtering data

## Getting Started
### Prerequisites
- Xcode installed on your Mac
- Swift knowledge (basic understanding of SwiftUI)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PersonalExpenseTracker.git
   ```
2. Open the project in **Xcode**.
3. Run the project using the **iOS Simulator**.

