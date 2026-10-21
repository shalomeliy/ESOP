# 💼 ESOP Enterprise Engine & Testbed

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-blue.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.11+" />
  <img src="https://img.shields.io/badge/FastAPI-0.100+-009688.svg?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Alembic-Migrations-red.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="Alembic" />
  <img src="https://img.shields.io/badge/Database-SQLite-003B57.svg?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

מערכת מקצה לקצה (End-to-End) לניהול, תרגול וסימולציה של חלוקת **אופציות / RSU**, התאמת מיסוי (ישראל 102 / ארה"ב ISO/NSO), ניהול נאמנים (Trustees) וסטטוסי עובדים.

---

## 📋 תוכן עניינים
1. [🚀 מדריך הרצה מהירה (Quick Start)](#-מדריך-הרצה-מהירה-quick-start)
2. [🔑 גישה למערכת ומשתמשי דמו](#-גישה-למערכת-ומשתמשי-דמו)
3. [🗄️ ניהול מיגרציות וסכמת DB (Alembic)](#️-ניהול-מיגרציות-וסכמת-db-alembic)
4. [🧪 מעבדת באגים ובדיקות (QA Testbed)](#-מעבדת-באגים-ובדיקות-qa-testbed)

---

## 🚀 מדריך הרצה מהירה (Quick Start)

> 💡 **איך לחשוב על זה?**  
> ממש כמו לפתוח חנות צעצועים חדשה: קודם בונים את המדפים (מתקינים תוכנות), אחר כך ממלאים אותם בצעצועים (מכינים בסיס נתונים), ורק אז פותחים את הדלת ללקוחות (מדליקים את השרת).  
> **שלבים 0–3 מבוצעים פעם אחת בלבד במחשב חדש!**

### שלב 0: דרישות קדם (Prerequisites)
* **Python 3.11 ומעלה** — לבדיקה בטרמינל: `python --version`
* **Git** — להורדת הריפוזיטורי

### שלב 1: הורדת הקוד
```bash
git clone <כתובת-הריפו-שלכם>
cd ESOP_test
