# brutalist-ledger-Habit-Tracker-Diary

An ultra-modern, Neo-Brutalist habit tracker and expense management system designed for desktop and mobile efficiency.

##  Key Engineering Solutions
* **System-Synchronized Logic:** The application automatically fetches the user's system clock to generate dynamic month lengths, including leap-year logic.
* **Persistent Data Privacy:** Utilizes `localStorage` for 100% client-side data persistence. User data never touches a server, ensuring total privacy.
* **Responsive Data Visualization:** Features a vertical line-chart for sleep tracking that uses percentage-based coordinate math to remain accurate even when the UI is resized.
* **Advanced File Handling (The "Blob" Method):** Implemented a Binary Large Object (Blob) architecture for CSV exports. This bypasses browser URL character limits, ensuring that even long-form diary entries are safely packaged into a physical file for the user.

##  UI/UX Design Philosophy
This project follows **Neo-Brutalist** design principles:
* Stark, high-contrast black borders and solid shadows.
* Massive, dominating typography for chronological navigation.
* Neon-accented feedback (Emerald for positive habits, Crimson for penalties).
* Interactive "Log" and "Expense" modals to keep the main ledger clean.
