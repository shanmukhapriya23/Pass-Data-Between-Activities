# Task 12: Pass Data Between Activities

This repository contains an Android application built in Kotlin demonstrating how to pass user input data (`Name` and `Email`) from a primary screen (`MainActivity`) to a secondary screen (`SecondActivity`) using Android `Intent` extras.

---

## 📌 Project Overview

* **Goal**: Understand data transfer between Android Activities.
* **Input**: User enters their Name and Email address in `MainActivity`.
* **Output**: The entered details are displayed in `SecondActivity` upon clicking the submission button[cite: 1].

---

## 🛠️ Tools & Technologies

* **Language**: Kotlin[cite: 1]
* **IDE**: Android Studio[cite: 1]
* **UI**: XML Layouts (ConstraintLayout / LinearLayout)

---

## 📁 Repository Structure

```text
app/src/main/
├── java/com/example/datapasstask/
│   ├── MainActivity.kt      # Reads user input & launches SecondActivity
│   └── SecondActivity.kt    # Receives Intent extras & updates UI
└── res/layout/
    ├── activity_main.xml    # UI containing Input fields & Submit Button
    └── activity_second.xml  # UI displaying the received Name & Email
** Author Shanmukhapriya **
