# 📰 NewsYork – News Aggregation Website

NewsYork is a frontend-driven news aggregation web application that fetches real-time news using external APIs and allows users to interact with articles through comments, votes, and bookmarks.

This project is designed with **future backend integration in mind** and includes a fully prepared MySQL database schema.

---

## 🚀 Features

- 🗞️ Real-time news fetching using NewsAPI
- 💬 Comment system with profanity filtering
- 👍 Upvote / 👎 Downvote articles
- ⭐ Bookmark favorite articles
- ⚙️ Sidebar navigation & settings panel
- 🔐 MySQL database schema ready for backend integration

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript (Vanilla)

### Database
- MySQL
- phpMyAdmin (via XAMPP)

---

## 📁 Project Structure

```
NewsYork/
│
├── css/
├── js/
│   └── script.js
├── images/
├── index.html
├── signup.html
├── news_york.sql
└── README.md
```

---

## 🗂️ Database Setup (READ CAREFULLY)

⚠️ **Most common mistakes happen here — follow exactly**

### ✅ Requirements
- XAMPP installed
- MySQL started **ONLY from XAMPP Control Panel**
- phpMyAdmin accessible

---

## ▶️ Step 1: Start Services

Open **XAMPP Control Panel** and start:
- Apache ✅
- MySQL ✅

⚠️ Do NOT start/stop MySQL from `services.msc`

---

## ▶️ Step 2: Open phpMyAdmin

Open your browser and visit:

```
http://localhost/phpmyadmin
```

If this page opens → MySQL is running correctly.

---

## ▶️ Step 3: Import Database (`.sql` file)

1. In phpMyAdmin, click **Import**
2. Click **Choose File**
3. Select `news_york.sql`
4. Click **Go**

✅ This will:
- Create database `news_york`
- Create all required tables automatically

---

## ▶️ Step 4: Verify Import

In phpMyAdmin:
- Refresh page
- You should see database: `news_york`

Open it → Tables:
- users
- articles
- comments
- votes
- bookmarks

---

## ❗ Common MySQL Issues & Fixes

### ❌ MySQL shuts down unexpectedly
**Cause:** Another MySQL instance already using port 3306  
**Fix:**  
- Stop other MySQL services  
- Use MySQL only via XAMPP

---

### ❌ Access denied for user 'root'
**Fix (XAMPP default):**

```
mysql -u root
```

(Default root password is empty)

---

## ▶️ How to Run the Project

1. Start Apache & MySQL in XAMPP
2. Import `news_york.sql`
3. Open in browser:

```
http://localhost/NewsYork/index.html
```

---

## 🔮 Future Enhancements

- Backend integration (Spring Boot / Node / PHP)
- JWT-based authentication
- Persistent comments, votes & bookmarks
- User profiles
- Admin moderation panel

---

## 👨‍💻 Author

**Rohit More**  
Aspiring Backend Developer  
Java | Spring Boot | MySQL | REST APIs
