# ✅ TodoApp_Native (React Native Project)

This is a mobile **to-do list application** developed using **React Native (Expo)**.  
It allows users to **add, view, and manage tasks** with a simple interface.  
The app uses a **calendar view** to organize tasks by date and stores all data **locally using AsyncStorage** for offline access.

---

## 🔧 Technologies Used

- Framework: React Native (Expo)
- Language: JavaScript / TypeScript
- Navigation: Expo Router (Tabs)
- Local Storage: AsyncStorage
- Calendar: react-native-calendars
- Date Picker: react-native-modal-datetime-picker
- Icons: @expo/vector-icons

---

## 📁 Folder Structure

```bash
TodoApp_Native/
├── app/
│   ├── _layout.js        ← Tab navigation layout
│   ├── index.js          ← Home screen (Today's tasks)
│   ├── todo.js           ← Calendar + Task management screen
│
├── components/
│   ├── TabBar.js         ← Custom bottom tab bar
│   ├── CalendarView.js   ← Calendar view with marked dates
│   ├── TaskForm.js       ← Modal form for adding new tasks
│
├── assets/
│   └── homebanner.png    ← Banner image for home screen
│
├── package.json
├── app.json
└── README.md
```

## ⚙️ Setup Instructions

  1. Clone the repository
  
     Copy code
     ```bash
      git clone https://github.com/MadhushanSathsara/TodoApp_Native.git
      ```
     
     cd TodoApp_Native
  
  2. Install dependencies
     
     Copy code
      ```bash
      npm install
      ```
      
  4. Start the Expo development server

     Copy code
      ```bash
      npx expo start
      ```
      Then scan the QR code using the Expo Go app or run it on an emulator (Android/iOS).

### 📱 Features

#### 🗓 Calendar-based task organization

#### ➕ Add and delete tasks easily

#### 🔄 Update task status (Pending → In Progress → Done)

#### 💾 Offline storage using AsyncStorage

#### 🎨 Color-coded task tags

#### 🧭 Custom tab bar navigation


⚠️ Note: Editing existing tasks is not supported yet — only add, view, delete, and change status.



### 🧠 Core Functionality

* All tasks are stored locally under the key @tasks_storage

* Tasks include title, description, date, color, and status

* Home screen displays only today’s tasks

* Calendar highlights dates that contain tasks

Task status cycles through:

scss
Copy code

Pending → In Progress → Done → Pending
🚀 Future Enhancements
✏️ Edit existing tasks

🔔 Task reminders / notifications

☁️ Cloud sync (Firebase / Supabase)

🌙 Dark mode support

🤝 Author

Developed by Madhushan Sathsara

🔗 GitHub: MadhushanSathsara
