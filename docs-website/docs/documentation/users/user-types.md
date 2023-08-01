---
sidebar_position: 1
---

# User Types

In our system, we have the following user types:

| Role Id | User Type              | Description                                               |
|:--------|:-----------------------|:----------------------------------------------------------|
| 1       | undergraduate students| student who is still an undergraduate                     |
| 2       | graduate students     | student who graduated with at least a bachelor's degree   |
| 3       | instructor            | instructor who's responsible for classroom/course content |

Each user role has its own privilege, such as:
### Instructors 
- can perform CRUD operations on the course content (annocuments, comments,exams, etc..).
- assign exams to specific students.
- view all students grades

### Undergraduate VS Graduate students
there's no difference in terms of functionality but the only difference is, instructor can choose questions only visible to graduate students  
