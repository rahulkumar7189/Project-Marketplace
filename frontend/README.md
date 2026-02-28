# 🎨 AcadMate Frontend

The frontend of AcadMate delivers a premium, visually stunning user interface relying entirely on modern **Vanilla web technologies**. It is engineered for responsiveness, performance, and accessibility without the bloat of heavy front-end frameworks.

## 🛠️ Tech Stack

- **Structure:** HTML5
- **Style:** CSS3 (Vanilla + Custom Design System)
- **Logic:** Vanilla JavaScript (ES6+)

## 🚀 Setup & Execution

Since the frontend is entirely statically generated, setup is incredibly straightforward:

1. **Option A: Direct Browser Access**
   Simply open `index.html` directly in your favorite modern browser.

2. **Option B: Local Web Server (Recommended)**
   To ensure features like ES6 Modules or certain API integrations function properly without CORS issues, serve the directory locally.
   - Using Python:
     ```bash
     cd frontend
     python -m http.server 8080
     ```
   - Using Node.js (Live Server):
     ```bash
     cd frontend
     npx live-server
     ```

## 📂 Directory Structure Highlights

- `/css` — Contains our custom-built, premium design system and component styles.
- `/js` — Core functional logic handling dashboards, authentication flows, and API requests.
- `*.html` — The main entry points for different routes (e.g., `login.html`, `dashboard.html`, `admin.html`).

## 📄 License

This module is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
