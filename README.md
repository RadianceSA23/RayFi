# RayFi


# 💸 Expense Tracker – Android App (Kotlin)

A modern personal finance manager built with **Kotlin**, **Jetpack Compose**, **Room**, and **MVVM + Clean Architecture**. This app helps users efficiently track daily expenses, categorize them, visualize with charts, and export data for further analysis.

![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-blue?logo=android)
![Room DB](https://img.shields.io/badge/DB-Room-orange?logo=sqlite)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-purple?logo=kotlin)
![Architecture](https://img.shields.io/badge/Architecture-MVVM%20%2B%20Clean-success)

---

## ✨ Features

- ✏️ Add, edit, and delete expenses
- ⚖ Categorize expenses (e.g., Food, Travel, Bills)
- 📊 View monthly summaries via charts
- 📁 Export expense data as CSV
- 📱 Offline-first design with Room database
- 🔁 Optional Firebase Auth + Sync (Bonus)
- ⏰ Background data backup using WorkManager

---

## 🧱 Tech Stack

| Layer          | Tech Details                                                                 |
|----------------|------------------------------------------------------------------------------|
| Language       | Kotlin                                                                       |
| UI             | Jetpack Compose + Material3                                                  |
| Architecture   | MVVM + Clean Architecture + Repository Pattern                               |
| Local Storage  | Room Database + DAO                                                          |
| Background     | WorkManager + Coroutines                                                     |
| Charts         | MPAndroidChart / Compose chart libraries                                     |
| CSV Export     | OpenCSV / Kotlin `FileWriter`                                                |
| Cloud (Bonus)  | Firebase Authentication + Firestore (Synced using `StateFlow` and `LiveData`)|

---

## 📸 Screenshots

> _(Add screenshots here showing home screen, add expense screen, charts, and export dialog)_

---

## 🔧 Setup & Run Locally

```bash
git clone https://github.com/your-username/expense-tracker-compose.git
cd expense-tracker-compose
```

Open the project in **Android Studio Giraffe+** with Kotlin & Compose support enabled.

---

## 📂 Folder Structure

```
📦 app/
 ┣ 📂 data/
 ┃ ┣ 📂 local/         # Room DB, DAO, Entities
 ┃ ┣ 📂 remote/        # Firebase (optional)
 ┃ ┗ 📜 repository/
 ┣ 📂 domain/
 ┃ ┣ 📂 model/         # Business models
 ┃ ┗ 📂 usecase/       # Business logic
 ┣ 📂 presentation/
 ┃ ┣ 📂 ui/            # Compose UI screens
 ┃ ┣ 📂 viewmodel/     # ViewModels with StateFlow
 ┗ 📜 MainActivity.kt
```

---

## ✅ Best Practices

- Dependency Injection (Hilt/Koin)
- Clean Architecture with modular design
- StateFlow & LiveData combination
- Offline-first with proper caching
- Dark/Light theme support
- Compose Previews for UI testing

---

## 📤 Future Enhancements

- 🔔 Budget limit alerts
- 🔁 Recurring expenses
- 🌍 Multi-currency support
- 🧾 PDF report export
- 🔐 Biometric login

---

## 📃 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🙌 Credits

- [Jetpack Compose](https://developer.android.com/jetpack/compose)
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
- [OpenCSV](http://opencsv.sourceforge.net/)
- [Firebase](https://firebase.google.com/)

---

## 👨‍💻 Author

Made with ❤️ by [Subburaj](https://github.com/your-username)

