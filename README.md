# 🏋️‍♂️ Online Fitness Training Platform (Java Console Application)

A Java-based console application designed to connect **fitness enthusiasts**, **professional trainers**, and **system administrators** in one unified fitness management platform.

This project demonstrates concepts of **object-oriented programming**, **role-based access management**, and **real-world fitness workflow automation**.

---

## 🚀 Features by User Role

### 👤 Users (Members / Premium Members)
- Browse and enroll in workout plans
- Track fitness progress (exercise duration + calories burned)
- View personal progress history
- Manage profile information

### 🧑‍🏫 Trainers
- Create structured workout plans
- Add exercises to plans
- View all users enrolled in their plans

### 🔐 Administrators
- View all users, plans, and trainers
- Monitor system statistics
- Approve/manage users and overall platform operations

---

## 🛠️ Core Java Architecture

| Component | Description |
|----------|-------------|
| `User` | Handles user details, enrollments & progress logs |
| `Trainer` | Creates & manages workout plans |
| `WorkoutPlan` | Contains structured workout routines & exercises |
| `ProgressLog` | Stores workout logs with timestamps |
| `Administrator` | Manages accounts and platform statistics |
| `FitnessPlatform` | Main system orchestrating all components |

📌 **Storage:** In-memory data using `ArrayList`  
📌 **Design Pattern:** Multi-role modular architecture  

---

## 📌 Class Diagram (Overview)

```

Administrator ↔ FitnessPlatform ↔ User ↔ WorkoutPlan ↔ Trainer
↘
ProgressLog

```

---

## 📂 Project Structure

```

src/
│── FitnessPlatform.java
│── User.java
│── Trainer.java
│── WorkoutPlan.java
│── ProgressLog.java
│── Administrator.java

````

---

## ▶️ How to Run

1. Install **JDK 17+**
2. Compile the project:
   ```bash
   javac FitnessPlatform.java
````

3. Run the program:

   ```bash
   java FitnessPlatform
   ```

---

## 💡 Sample Functional Flow

```
Admin created ➝ Trainers created ➝ Plans added
          ⬇
     Users registered
          ⬇
     Users enroll in plans
          ⬇
  Workout progress logged
          ⬇
 Trainer views enrolled students
          ⬇
  Admin audits platform statistics
```

---

## 📝 Example Console Output Highlights

✔ Users enrolling in workout plans
✔ Progress logs with **date, exercise, duration & calories**
✔ Trainers viewing their students
✔ Administrator viewing system statistics

---

## 📈 Future Enhancements (Roadmap)

| Planned Feature                         | Status    |
| --------------------------------------- | --------- |
| Database Integration (JDBC / MySQL)     | ⏳ Pending |
| GUI Web Dashboard / JavaFX              | ⏳ Pending |
| Payment & subscription handling         | ⏳ Pending |
| Video-based exercise tutorials          | ⏳ Pending |
| Mobile App (Android)                    | ⏳ Pending |
| Analytics dashboard for trainers/admins | ⏳ Pending |

---

## 👥 Team Members

| Name          |
| ------------- |
| Jatin Kaushik |
| Aditya Singh  |
| Ayush Singh   |

---

## 📜 License

This project is open-source for academic and learning purposes.

---

### ⭐ If you like this project, don’t forget to star the repository on GitHub!

```

---

If you'd like, I can also:
✔ generate a project logo  
✔ add GitHub badges (e.g., Java version, license, contributors)  
✔ create a wiki documentation page  

Want me to auto-create a **GitHub repository structure with all files**? 🚀
```
