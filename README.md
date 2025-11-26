# 📱 Instagram Login UI – Android App  

A modern, clean, and dark-themed **Instagram-style Login Page** built using **Android XML and Kotlin**.  
This project demonstrates Android UI design, drawable shape usage, custom button styling, and Kotlin event handling.

---

## 🚀 Features
- ✔ Instagram-inspired login screen  
- ✔ Dark theme with premium blue & black shades  
- ✔ Rounded dark-blue Login button  
- ✔ Toast popup message: *"Login is Successful"*  
- ✔ Editable logo, theme, and colors  
- ✔ Beginner-friendly Kotlin code  
- ✔ Fully responsive and organized layout  

---

## 📸 App Screen Overview
- Logo section at the top  
- Username and password fields  
- Rounded Login button  
- “OR” separator  
- “Login with Facebook” section  
- “Forgot Password?”  
- Bottom sign-up panel  

---

## 🛠 Tech Stack
- **Android Studio**  
- **Kotlin**  
- **XML Layout**  
- **Drawable Shape XML**  
- **Toast Notification**  

---

## 📂 Project Structure
app/
└── src/
└── main/
├── java/com/example/myapplication3/MainActivity.kt
├── res/
│ ├── layout/activity_main.xml
│ ├── drawable/button_bg.xml
│ ├── drawable/img.png (logo)
│ ├── drawable/img_13.png (facebook icon)
│ └── values/colors.xml

pgsql
Copy code

---

## 🧩 Core Code Files

### 🔹 **Login Button (activity_main.xml)**

```xml
<Button
    android:id="@+id/btnLogin"
    android:layout_width="match_parent"
    android:layout_height="50dp"
    android:text="Login"
    android:textSize="22sp"
    android:textColor="#FFFFFF"
    android:background="@drawable/button_bg"
    android:onClick="loginClicked" />
🔹 Rounded Button Background (button_bg.xml)
xml
Copy code
<shape xmlns:android="http://schemas.android.com/apk/res/android">
    <solid android:color="#021C3E"/>
    <corners android:radius="12dp"/>
</shape>
🔹 Kotlin Code – Toast Popup (MainActivity.kt)
kotlin
Copy code
fun loginClicked(view: View) {
    val toast = Toast.makeText(this, "Login is Successful", Toast.LENGTH_SHORT)
    toast.setGravity(Gravity.TOP or Gravity.CENTER_HORIZONTAL, 0, 120)
    toast.show()
}
🧪 How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/Instagram-Login-UI-Android.git
Open the project in Android Studio

Connect emulator or phone

Run the app

🎯 Purpose of This Project
This project was created to practice:

Android UI design

Input fields & button interactions

Kotlin functions

XML drawable backgrounds

Building an Instagram-like login screen

📝 License
This project is free to use for personal and educational purposes.

👨‍💻 Author
Kumar Shanu
Android Developer • Student • Tech Learner

yaml
Copy code
