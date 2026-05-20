# פרויקט קורס — Smart Event Management System

## תיאור הפרויקט

במהלך הקורס נבנה מערכת מודרנית לניהול אירועים.

המערכת תאפשר:
- ניהול אירועים
- ניהול משתמשים
- Dashboard
- חיפוש וסינון
- סטטיסטיקות
- עבודה רספונסיבית
- עבודה עם AI לאורך כל תהליך הפיתוח

---

# מטרות הפרויקט

הפרויקט נועד לתרגל:

- עבודה נכונה עם AI
- Prompt Engineering
- System Design
- Frontend Development
- עבודה עם Components
- Responsive Design
- Architecture Thinking
- Refactoring
- עבודה מסודרת עם GitHub

---

# טכנולוגיות

הפרויקט יתבסס על:

- React
- Tailwind CSS
- StackBlitz
- ChatGPT
- Cursor
- GitHub

---

# שלב 1 — אפיון המערכת

## הגדירו:

### סוגי משתמשים
- Admin
- Event Organizer
- Participant

---

## Features עיקריים

### Dashboard
הצגת מידע מרכזי על אירועים.

### Events Management
יצירה וניהול אירועים.

### Statistics
סטטיסטיקות ונתונים.

### Search & Filters
חיפוש וסינון אירועים.

### Notifications
התראות למשתמשים.

---

## שאלות שצריך לחשוב עליהן

- איזה מידע נשמור?
- איזה מסכים יהיו?
- אילו פעולות המשתמש יכול לבצע?
- אילו APIs נצטרך?

---

# שלב 2 — פירוק המערכת (Decomposition)

## חלקו את המערכת לחלקים קטנים

### Authentication
- Login
- Logout

---

### Dashboard
- Statistics Cards
- Recent Events
- Notifications

---

### Events
- Events Table
- Event Details
- Create Event

---

### Filters
- Search
- Date Filter
- Category Filter

---

## המטרה

לא לעבוד על:
"Build full system"

אלא:
לבנות חלקים קטנים בצורה מסודרת.

---

# שלב 3 — כתיבת Prompt מקצועי

## כתבו Prompt ברור ומפורט

### Prompt לדוגמה

```text
Build a responsive dashboard for managing events.

Requirements:
- Sidebar navigation
- Events table
- Statistics cards
- Search and filters
- Dark mode
- Mobile responsive

Use React and Tailwind CSS.
Generate reusable components separately.
