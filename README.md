# 🎓 Agentic AI Attendance Advisor

📌 Project Overview

The **Agentic AI Attendance Advisor** is an education-focused mini project that analyzes student attendance records and automatically provides personalized recommendations. The project demonstrates the concept of **Agentic AI** by following the **Observe → Decide → Act** workflow.

---

 🎯 Objective

The objective of this project is to:
- Analyze student attendance data.
- Identify students with excellent, good, or low attendance.
- Automatically generate personalized recommendations.
- Reduce the manual effort required by faculty members.

---

 🤖 Agent Used

 Rule-Based Decision Agent

This project uses a **Rule-Based Decision Agent**.

The agent:
- Observes student attendance.
- Makes decisions using predefined rules.
- Automatically generates recommendations.

This follows the Agentic AI workflow:

Observe → Decide → Act

---

 ⚙️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Kaggle Dataset

---

 📂 Dataset

Source: Kaggle Student Attendance Dataset

The dataset contains student attendance records used to generate personalized recommendations.

---

 🔄 Project Workflow

```
Student Attendance Dataset
            │
            ▼
Load Dataset using Pandas
            │
            ▼
Analyze Attendance Percentage
            │
            ▼
Rule-Based Decision Agent
            │
            ▼
Generate Personalized Recommendation
            │
            ▼
Save Output as CSV
```

---

 💻 Working

The AI agent evaluates each student's attendance:

- Attendance ≥ 85%
  - Excellent Attendance
  - Recommendation: Keep up the good work.

- Attendance between 75% and 84%
  - Good Attendance
  - Recommendation: Maintain your attendance.

- Attendance < 75%
  - Low Attendance
  - Recommendation: Attend extra classes and meet your faculty advisor.

The recommendations are automatically stored in a new CSV file.

---

📊 Output

The project generates:

```
Attendance_Advisor_Output.csv
```

The output file contains:

- Student Details
- Attendance Percentage
- AI Generated Recommendation



 🌟 Features

- Automated attendance analysis
- Personalized recommendations
- Rule-based intelligent decision making
- Easy to understand
- Suitable for educational institutions



 🎯 Use Cases

- Schools
- Colleges
- Universities
- Student Monitoring Systems
- Academic Performance Support



 🚀 Future Enhancements

- Email notifications to students
- SMS alerts for low attendance
- Dashboard visualization
- College ERP integration
- Machine Learning-based attendance prediction
- LLM-powered conversational attendance assistant



 📁 Project Structure


Agentic-AI-Attendance-Advisor/
│
├── Agentic_AI_Attendance_Advisor.ipynb
├── attendance.csv
├── Attendance_Advisor_Output.csv
├── README.md
├── requirements.txt
├── LICENSE
```


 📜 License

This project is licensed under the MIT License.

--Dadi Institute of Engineering and Technology

Academic Year: 2025–2026
