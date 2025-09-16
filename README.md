
---
# Employee Management System (JavaScript + HTML)

This is a simple **Employee Management System** built using HTML and JavaScript.  
It demonstrates basic operations such as displaying employee details, calculating salaries, filtering by department, and searching by ID or specialization.

---

## 🚀 Features
- **Display Employees**: Shows the list of all employees with details.
- **Calculate Total Salaries**: Calculates and displays the total salary of all employees.
- **Display HR Employees**: Filters and displays only employees from the HR department.
- **Find Employee by ID**: Searches for an employee using their unique ID.
- **Find by Specialization (JavaScript)**: Displays employees with a JavaScript specialization.

---

## 🗂️ Project Structure


## 📜 Code Overview

### Employee Data
Employees are stored in an array of objects:
```javascript
const employees = [
  { id: 1, name: 'John Doe', age: 30, department: 'IT', salary: 50000, specialization: 'JavaScript' },
  { id: 2, name: 'Alice Smith', age: 28, department: 'HR', salary: 45000, specialization: 'Recruitment' },
  { id: 3, name: 'Bob Johnson', age: 35, department: 'Finance', salary: 60000, specialization: 'Accounts' },
  { id: 4, name: 'Emily Davis', age: 26, department: 'IT', salary: 55000, specialization: 'JavaScript' },
];
