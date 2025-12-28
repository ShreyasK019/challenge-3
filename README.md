# MindfulScroll

**MindfulScroll** is a mini-project designed to help users become aware of their social media usage patterns. Often, we use apps like Instagram or TikTok not for productive purposes, but for mindless scrolling — consuming content without any specific goal. This project aims to **detect whether a social media session is intentional or mindless**, using AI logic, and display results in a modern, interactive web interface.

---

## 🎯 Problem Statement

Social media usage can often lead to procrastination and wasted time. Users typically:
- Spend more time than intended scrolling content.
- Frequently switch between apps without purpose.
- Lack awareness of their digital habits.

**MindfulScroll** provides a solution by:
- Monitoring session metrics (time spent, scroll count, app switches).  
- Using AI to classify the session as either **Intentional Usage** or **Mindless Scrolling**.  
- Providing instant feedback to encourage more conscious social media habits.

---

## 💡 Features

### Core Features
- **AI Intent Detection:** Classifies sessions based on simple session metrics.  
- **Frontend Interface:** Modern, responsive, and user-friendly.  
- **Multiple Input Options:** Users provide time spent, scroll count, and app switches.  
- **Instant Feedback:** Clear display of session type.

### AI Feature
- **Logic:** A rule-based simulation of Logistic Regression (Python) or direct JS logic.  
- **Input Features:**  
  - `time_spent` (minutes)  
  - `scroll_count` (number of scrolls)  
  - `app_switches` (number of app switches)  
- **Output:**  
  - `"Intentional Usage"` ✅  
  - `"Mindless Scrolling"` ⚠️  

> Optional: Full Python backend can use real Logistic Regression with scikit-learn.

### Frontend
- Responsive design suitable for desktop and mobile.  
- Clean card layout with gradient background.  
- Hover effects on buttons and interactive result display.  
- Multiple HTML versions for experimentation.

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend (optional):** Python, Flask  
- **AI:** scikit-learn (for Logistic Regression in backend version)  
- **Libraries:** pandas, Flask  

---

## 🚀 How to Run the Project

### Option 1: Frontend Only
1. Open `frontend/index.html` in any browser.  
2. Enter session details (time spent, scroll count, app switches).  
3. Click **Analyze** to see instant AI feedback.

### Option 2: Full Backend with AI
1. Activate Python virtual environment:

```bash
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
