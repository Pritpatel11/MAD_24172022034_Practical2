# 📘 MAD_24172022034_Practical2:  Understanding Activity Lifecycle & Simple UI in Android

## 🎯 Objective
The objective of this practical is to demonstrate how the **Activity Lifecycle** works in Android, along with creating a basic user interface that includes a styled "Hello World" text and lifecycle feedback via Toasts, Logs, and Snackbars.

---

## 🔑 Key Features
- **Lifecycle Demonstration**  
  Implement all lifecycle methods (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onRestart`, `onDestroy`) so that each one:  
  - Shows a `Toast`  
  - Prints a `Log` message  

---

## 📑 Contents
1. [How to Run](#how-to-run)  
2. [App Structure](#app-structure)  
3. [Testing the Lifecycle](#testing-the-lifecycle)  
4. [Screenshots](#screenshots)  
5. [Lifecycle Explanation](#lifecycle-explanation)  
6. [Additional Notes](#additional-notes)  

---

## 🚀 How to Run
1. Download or clone this repository.  
2. Open the project in **Android Studio**.  
3. Run it on an emulator or a physical Android phone.  
4. Interact with the app to see:  
   - The **"Hello World"** UI  
   - Lifecycle logs in **Logcat**  
   - Toast & Snackbar notifications for each lifecycle method  

---

## 🔄 Testing the Lifecycle
- Launch the app → `onCreate`, `onStart`, `onResume` are called  
- Press **Home** or switch apps → `onPause`, then `onStop`  
- Return to the app → `onRestart`, `onStart`, `onResume`  
- Close the app → `onDestroy`  

You’ll see **Log messages**, **Toasts**, and **Snackbars** for every state change.  

---

## 📷 Screenshots
Examples of the UI and lifecycle logs:  

<p float="left">
  <img src="app/screen.png" alt="Screenshot 1" width="200"/>
  <img src="app/img.png" alt="Screenshot 2" width="800"/>
</p>  

---

## 📚 Lifecycle Explanation
- **`onCreate()`** → Initializes the activity and UI  
- **`onStart()`** → Activity is visible  
- **`onResume()`** → Activity is ready for user input  
- **`onPause()`** → Activity is partially hidden  
- **`onStop()`** → Activity is fully hidden  
- **`onRestart()`** → Called when coming back from `onStop()`  
- **`onDestroy()`** → Final cleanup before removal  

➡ Flow: **Create → Start → Resume → Pause → Stop → Restart/Destroy**  

---
