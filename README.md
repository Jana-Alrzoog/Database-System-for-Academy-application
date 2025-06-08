<h1 align="center"> Database System for Academy Application</h1>

<p align="center">
  A relational database designed to support interactive educational platforms with structured and efficient data handling.
</p>

---

## 📘 Project Description

This project focuses on designing and implementing a robust **relational database** system tailored for an online educational platform. The system ensures efficient management of student and instructor information, course structures, and assignment workflows, forming the backbone of an interactive and scalable learning environment.

---

## ✨ Key Features

- 👤 **User Management**  
  Manage student and instructor profiles, including registration, login, course enrollment, and tracking progress.

- 📚 **Course & Section Management**  
  Organize academic content into structured sections, assign instructors, and manage start/end dates.

- 📝 **Assignment Management**  
  Create, update, and track assignments linked to specific courses, with support for deadlines and status.

- 🔐 **Data Integrity**  
  Maintain data consistency through normalized schema design and enforced relationships between entities.

- 🔍 **Dynamic Queries**  
  Run advanced queries such as:
  - Listing courses with enrollment numbers  
  - Filtering assignments by due date or course  
  - Tracking student progress within sections

---

## 🧩 Entity Overview

| Entity      | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `Student`   | Stores student info, enrollment details, and course participation records.  |
| `Instructor`| Contains teacher data, including teaching field and contact info.           |
| `Section`   | Defines organizational structure with start/end dates for course grouping.  |
| `Course`    | Details individual programs, their content, and associated instructors.     |
| `Assignment`| Tracks student tasks with deadlines and links to specific courses.          |

---


## 📄 License

This project is licensed under the **MIT License**.  
For more information, see the [LICENSE](./LICENSE) file in this repository.

---

> 💡 This system is the foundation of a scalable academic platform, ensuring reliable, organized, and efficient educational data management.
