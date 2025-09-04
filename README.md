#BookMarkApp
# 📑 Bookmark App

A fully functional **Bookmark Manager** built using **HTML, CSS, and Vanilla JavaScript**.  
The app allows users to **save, edit, delete, and search bookmarks** directly in their browser with persistent storage using the **localStorage API**.  

This project was created to demonstrate **DOM Manipulation**, **Event Handling**, and **Client-Side Storage** in JavaScript — without using any external libraries or frameworks.  

---

## ✨ Features

✅ **Add Bookmarks** — Enter a title and URL to create a new bookmark  
✅ **Edit Bookmarks** — Update existing saved bookmarks without reloading  
✅ **Delete Bookmarks** — Remove bookmarks with one click (with confirmation)  
✅ **Search & Filter** — Real-time filtering of bookmarks using input events  
✅ **Sort Options** — Sort by Newest, Oldest, or Alphabetically (A–Z / Z–A)  
✅ **Persistent Storage** — Bookmarks are saved in `localStorage` and remain even after a page reload  
✅ **Responsive Design** — Works on desktop, tablet, and mobile devices  

---

## 🛠️ Technologies Used

- **HTML5** → Semantic structure for accessibility and SEO  
- **CSS3** → Custom styling (optionally Tailwind or Bootstrap can be used)  
- **Vanilla JavaScript (ES6+)** → Core functionality using:  
  - DOM Manipulation (`querySelector`, `createElement`, `appendChild`, etc.)  
  - Event Handling (`click`, `submit`, `input`)  
  - `localStorage` for persistence  

---

## ⚙️ How It Works

The Bookmark App works entirely on the **client-side** (no server required):  

1. **Initialization**  
   - On page load, the app checks `localStorage` for saved bookmarks.  
   - If found, they are loaded and dynamically rendered in the bookmarks list using DOM methods.  

2. **Adding Bookmarks**  
   - User submits the form (title + URL).  
   - JavaScript validates the input (valid URL, no duplicates, not empty).  
   - Bookmark is added to an array, saved to `localStorage`, and the DOM updates instantly.  

3. **Editing & Deleting**  
   - Each bookmark card has `Edit` and `Delete` buttons.  
   - Edit opens the form with existing data, allowing updates.  
   - Delete removes the bookmark from the array, updates `localStorage`, and re-renders the DOM.  

4. **Searching & Filtering**  
   - A search bar listens for `input` events.  
   - As the user types, the bookmarks array is filtered and only matching bookmarks are rendered.  

5. **Persistence**  
   - Every update (add/edit/delete) is saved back to `localStorage`.  
   - Even after refreshing or closing the browser, bookmarks remain intact.  

---



## 📂 Project Structure

