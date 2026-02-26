# FlaskAuthApp

## 📌 Assignment: Registration Validation

This project is a Flask-based authentication system. The main goal of this assignment was to fix the registration form validation issue using backend (server-side) validation.

---

## 🚨 Problem

Earlier, the registration form was submitted even when:

* Name was empty
* Email was empty
* Password was empty

This was incorrect and needed proper validation.

---

## ✅ Solution

The following validations were implemented in the `/register` route:

1. Name must not be empty
2. Email must not be empty
3. Password must not be empty
4. Email must be unique
5. Password must be at least 6 characters
6. Proper error messages are displayed

Server-side validation is used to improve security.

---

## 💻 GitHub Repository

(https://github.com/uditbhatt55/flaskauthapp)

---

## 🛠 Tech Stack

* Python
* Flask
* HTML
* CSS
* Bootstrap
* SQLite

---

## ⚙️ How to Run

Clone the project:

```bash id="t7g8h9"
git clone https://github.com/your-username/flaskauthapp.git
```

Go to project folder:

```bash id="i8j9k0"
cd flaskauthapp
```

Install dependencies:

```bash id="k9l0m1"
pip install -r requirements.txt
```

Run the app:

```bash id="l0m1n2"
python app.py
```

---

## 📄 Note

This project was created as part of an academic assignment.

---

## 👨‍💻 Author

Udit Bhatt
B.Tech Student
