# 🤖 PenPalRobot Mentorship Hub

Welcome to the central command for our student robotics team. Below you will find the individual engineering notebooks and blog pages for each of our student builders. 

Select a student below to check out their progress, photos, and builds!

---

## 👥 Student Engineering Notebooks

| Student Name | Project Focus | Notebook Link |
| :--- | :--- | :--- |
{% for student in site.data.students %}

| **{{ student.name }}** | {{ student.project }} | [View Blog 🚀](https://github.io{{ student.repo }}/) |
{% endfor %}

---
*Mentors: To add a new student, simply update the `_data/students.yml` file.*
