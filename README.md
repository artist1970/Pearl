# Pearl App Studio

**Pearl** is your sovereign “mini-Wix” — a self-hosted hub where you can launch, organize, and grow your own collection of web apps (games, wellness tools, news widgets, learning portals, and more) without relying on any external builder platform.

Everything is built with **plain HTML, CSS, and vanilla JavaScript**, so it’s easy to embed, remix, or migrate as your ecosystem grows.

---

## ✨ Core Idea

Pearl is:

- A **home screen** for all your apps (like a launcher).
- A **clean front-end shell** you fully control.
- A stepping stone toward **migrating away from Wix** into your own sovereign infrastructure.

Each app is a standalone HTML file in `/apps`, and the `index.html` file acts as the portal that links them all together.

---

## 🧩 Current Apps

These are examples of apps that can live inside `Pearl/apps` and be launched from the hub page:

- **Sudoku Sanctuary**  
  Unique-solution Sudoku with difficulty levels, conflict highlighting, and a mobile keypad.

- **Environment News App**  
  Environment-focused news reader with RSS feeds, favorites, and text-to-speech.

- **Lunar Reflections**  
  Moon-phase tracker with nightly reflection/journaling features.

- **6-Week Wellness Portal (Verve N Veda)**  
  Lessons, student workbook, habit trackers, nutrition portal, and a cloud-style notes area (localStorage-based).

> Each app is a self-contained HTML file, but they share a common visual language through the Pearl hub.

---

## 🧱 Project Structure

Recommended structure:

```text
Pearl/
  index.html              # Main Pearl hub / app launcher
  README.md               # This file
  /apps                   # Standalone apps (each is Wix-friendly HTML)
    sudoku.html
    environment-news.html
    lunar-reflections.html
    wellness-6week.html
  /assets                 # Shared images, icons, fonts (optional)
    ...
