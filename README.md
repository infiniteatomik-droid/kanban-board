#  Clean Kanban Board (Vanilla TS)

A minimalist, high-performance Kanban board built with pure TypeScript and Vite. Features a modern glassmorphism UI, smooth drag-and-drop mechanics, and persistent local storage.

##  **Live Demo:** [infiniteatomik-droid/kanban-board]

##  Tech Stack & Features

- **Core:** Pure TypeScript (Vanilla TS) with strict type-safety (`0 errors` in compiler).
- **Build Tool:** Vite for ultra-fast bundling and asset optimization.
- **UI/UX:** Modern Glassmorphism styling, responsive layout, and interactive state changes.
- **Data Persistence:** LocalStorage integration to save tasks across browser sessions.
- **Architecture:** Modular component-free structure using native DOM-manipulation under TS interfaces.

##  Project Structure

- `src/main.ts` — Application entry point, core event listeners, and DOM rendering.
- `src/types.ts` — Strict TypeScript interfaces (`KanbanTask`, `ColumnType`).
- `src/style.css` — Custom CSS with CSS Variables for theme management.

##  How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Build for production:
   ```bash
   npm run build
   ```
