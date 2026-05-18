📚 Akshara-Deepa Tutor

Akshara-Deepa Tutor is an offline Android learning application designed for SSLC students.  
The application helps students track syllabus completion, attend self-check quizzes, monitor academic progress, and identify weak subject areas using visual performance analytics.

---

🚀 Features

- 🔐 Login and Registration System
- 📖 Subject-wise Syllabus Tracking
- ✅ Chapter Completion Monitoring
- 📝 Self-Check Quiz System
- ⏱️ Timer-Based Quiz Evaluation
- 📊 Quiz Result Analysis
- 🕸️ Spider Web Strength Map Visualization
- 📈 Subject-wise Performance Analytics
- 💾 Offline Data Storage
- 📱 User-Friendly Android Interface

---

🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Java | Application logic and backend processing |
| Android Studio | Android application development |
| XML Layouts | UI design and screen creation |
| Room Database (SQLite) | Offline data storage |
| RecyclerView | Dynamic syllabus and chapter display |
| SharedPreferences | Session management |
| LiveData | Real-time UI updates |
| MPAndroidChart | Strength Map visualization |
| Executor Threads | Background database operations |

---

📱 Application Workflow

1. Student logs into the application  
2. Selects subject and chapter  
3. Marks chapters as completed  
4. Attends self-check quizzes  
5. Quiz scores are calculated automatically  
6. Progress is stored locally using Room Database  
7. Spider Web Strength Map updates dynamically  
8. Student identifies strong and weak subject areas  

---

🎯 Problem Statement

Many SSLC students face difficulty in tracking syllabus completion, monitoring academic progress, and identifying weak subject areas during self-study. Traditional study methods do not provide proper performance analysis or structured learning tracking.

Akshara-Deepa Tutor solves this problem by providing:

- Syllabus tracking
- Self-check quizzes
- Offline learning support
- Visual performance analysis

---

📊 Key Modules

🔐 Authentication Module
- Login and Registration
- Session Management

📚 Learning Module
- Subject and Chapter Tracking
- Syllabus Completion Monitoring

📝 Quiz Module
- MCQ-based self-check quizzes
- Automatic score calculation

📈 Analytics Module
- Spider Web Strength Map
- Subject-wise performance tracking

💾 Offline Storage Module
- Room Database integration
- Local data persistence

---

🧠 Strength Map Visualization

The application uses MPAndroidChart RadarChart to generate a Spider Web Strength Map that visually represents:

- Subject mastery levels
- Weak subject areas
- Strong subjects
- Academic performance analytics

---

📂 Project Structure

```bash
Akshara-Deepa-Tutor/
│
├── app/
├── java/
├── res/
│   ├── layout/
│   ├── drawable/
│   ├── values/
│
├── database/
├── adapters/
├── activities/
├── models/
└── README.md
