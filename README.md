# 🎒 Back2You – Smart Item Recovery Portal

<p align="center">
  <b>Lost Something? Found Something? Let's Bring It Back to You!</b>
</p>

<p align="center">
  A smart and centralized web platform designed to simplify the process of reporting, searching, and recovering lost and found items.
</p>

---

## 🌟 About the Project

**Back2You – Smart Item Recovery Portal** is a Flask-based web application that helps users report lost belongings, share information about found items, and browse item listings through a centralized platform.

The goal of this project is to make item recovery easier, more organized, and accessible by helping people reconnect with their misplaced belongings.

## ✨ Key Features

* 🔐 **User Authentication** – User registration and login.
* 📦 **Report Lost Items** – Report belongings that have gone missing.
* 🔎 **Report Found Items** – Share details about items that have been found.
* 🗂️ **Browse Items** – Explore lost-and-found item listings.
* 🗄️ **Database Integration** – Store application information using SQLite.
* 🎨 **User-Friendly Interface** – A web interface built with HTML, CSS, and Bootstrap.

## 🛠️ Technologies Used

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Python     | Backend programming       |
| Flask      | Web application framework |
| SQLite     | Database management       |
| HTML5      | Web page structure        |
| CSS3       | Styling and layout        |
| Bootstrap  | Responsive UI components  |
| JavaScript | Client-side interactions  |

## 📁 Project Structure

```text
BackToYou/
│
├── app.py
├── database.py
├── mywebsite.db
│
├── static/
│   └── css/
│       ├── foot.css
│       ├── index.css
│       ├── login.css
│       ├── nav.css
│       ├── register.css
│       └── report_lost.css
│
└── templates/
    ├── index.html
    ├── dashboard.html
    ├── login.html
    ├── register.html
    ├── browse_item.html
    ├── report_lost.html
    ├── report_found.html
    ├── nav.html
    └── foot.html
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/SamuWagh/BackToYou-Smart-Item-Recovery-Portal.git
```

### 2. Navigate to the Project Folder

```bash
cd BackToYou-Smart-Item-Recovery-Portal
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

```bash
pip install flask
```

Install any additional packages required by the project if necessary.

### 5. Run the Application

```bash
python app.py
```

Open the local URL displayed in your terminal. By default, Flask commonly uses:

`http://127.0.0.1:5000`

## 🎯 Project Objective

To provide a centralized platform where users can report missing belongings, share found-item information, and make the recovery process simpler and more efficient.

## 🔮 Future Enhancements

* 📧 Email notifications for item updates.
* 🖼️ Image uploads for lost and found items.
* 🔍 Advanced search and filtering.
* 📱 Improved mobile experience.
* 🤖 AI-assisted item matching.

## 👩‍💻 Author

**Samruddhi Wagh**

---

<p align="center">
  <b>Back2You — Every Lost Item Deserves a Way Back Home. 💙</b>
</p>
