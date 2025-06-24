# Novel-Graphical-Password-Authentication
This project introduces a novel graphical password authentication system aimed at enhancing both security and usability in user login mechanisms. Traditional text-based password systems suffer from issues like weak password selection, difficulty in remembering complex passwords, and vulnerability to brute-force or dictionary attacks.
# 🔐 A Novel Graphical Password Authentication Scheme

This project implements a **graphical password authentication** system with an improved focus on **usability** and **security**. Unlike traditional text-based passwords, this system allows users to authenticate using a sequence of images, making it more intuitive and harder to crack.

---

## 📌 Features

- 🔏 **Secure Image-Based Authentication**
- 🎯 Enhanced **usability** and **user experience**
- 🔄 Resistance to **shoulder-surfing attacks**
- 📸 Image grid-based **password selection**
- 🧠 Easy to remember and difficult to guess

---

## 🚀 Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask / Django) or PHP / Java (customizable)
- **Database**: MySQL / SQLite / MongoDB
- **Libraries/Frameworks**: Bootstrap, Flask (if used), Pillow (for image processing)

---

## 🛠️ How It Works

1. **Registration Phase**:
   - User selects a sequence of images from a displayed grid.
   - This sequence is stored securely (e.g., as hashed coordinates or indexes).

2. **Login Phase**:
   - User must select the same image sequence in the correct order to authenticate.

3. **Security Logic**:
   - Prevents brute-force attacks by limiting login attempts.
   - Protects against shoulder surfing by randomizing image positions.

---

## 📷 Screenshots

| Registration | Login |
|--------------|-------|
| ![Register](screens/register.png) | ![Login](screens/login.png) |

*(Update these with your actual project screenshots)*

---

## 📂 Folder Structure

project-root/
│
├── templates/ # HTML Templates
├── static/ # CSS, JS, Images
├── app.py # Main Python/Flask Application
├── db/ # Database files
├── README.md # Project description
└── requirements.txt # Dependencies


---

## 🧪 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/graphical-password-auth.git
   cd graphical-password-auth

pip install -r requirements.txt

python app.py

http://127.0.0.1:5000

