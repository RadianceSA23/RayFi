# RayFi

Expense Tracker - Android App (Kotlin)

A modern expense tracking application built using **Kotlin**, **Jetpack Compose**, **Room**, and **MVVM architecture**. This app helps users manage their finances by tracking daily expenses, categorizing them, visualizing with charts, and exporting data.

---

## ✨ Features

* ✉ Add, edit, delete expenses
* ⚖ Categorize expenses (e.g., Food, Travel, Bills)
* 📊 Chart view for monthly summaries
* 📃 Export expenses as CSV
* 📱 Offline-first with Room (local DB)
* ☁ Optional Firebase sync and auth (Bonus)

---

## 📁 Folder Structure

```
com.example.expensetracker
|
|│-- data                # Room DB, DAOs, Repositories
|│-- domain              # Models and Use Cases
|│-- presentation        # ViewModels and Composables (Screens/UI)
|│-- utils               # Constants, Extensions
|│-- worker              # Background sync using WorkManager
|└-- MainActivity.kt     # App Entry Point
```

This project uses **MVVM + Clean Architecture** principles.

---

## ⚙ Tech Stack

* **Language:** Kotlin
* **UI:** Jetpack Compose
* **Architecture:** MVVM + Clean Architecture
* **Local Storage:** Room Database
* **Background Tasks:** WorkManager with Coroutines
* **Charts:** MPAndroidChart (or Compose alternatives)
* **Export CSV:** OpenCSV (or custom file writer)
* **Optional:** Firebase Auth + Firestore for sync

---

## ⚡ Setup Instructions

### Prerequisites:

* Android Studio Dolphin or above
* Kotlin 1.8+
* Gradle 8+

### Clone and Run:

```bash
git clone https://github.com/yourname/expense-tracker-kotlin.git
cd expense-tracker-kotlin
```

Open the project in Android Studio, then click **Run**.

---

## ⏳ Future Improvements

* Income tracking
* Budget goals
* Recurring expenses
* Cloud backup via Firebase

---

## ❤ Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you would like to change.

---

## © License

MIT License. See `LICENSE` file for more info.

