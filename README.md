 🎨 Visuals — Interactive Image Gallery

A modern, responsive **interactive image gallery web application** built using **HTML, CSS, and Vanilla JavaScript**.
The project provides dynamic filtering, multiple layout views, and a full-screen lightbox viewer with image effects — all without any external frameworks.

 📌 Overview

**Visuals** is a front-end web project that displays a collection of images categorized into themes such as Nature, Urban, Portrait, Abstract, and Architecture.
Users can browse images in different layouts, apply filters, and view them in an immersive lightbox mode.

The entire application runs in the browser — no backend or database is required.



✨ Features

🖼️ Gallery System

* Dynamic image rendering
* Category-based filtering
* Real-time image count display
* Smooth animations while loading images

🔍 Filter Categories

* All
* Nature
* Urban
* Portrait
* Abstract
* Architecture

 📐 Multiple Layout Modes

* **Grid View** – Default responsive grid
* **Masonry View** – Pinterest-style layout
* **List View** – Compact list layout with details

🔦 Lightbox Viewer

* Full-screen image preview
* Previous / Next navigation
* Keyboard controls (Arrow keys & ESC)
* Touch swipe support (mobile)
* Image description and category display

🎨 Image Effects (Inside Lightbox)

Users can apply filters to images:

* Black & White
* Sepia
* Vivid
* Invert
* Hue Rotation
* Brightness adjustment

 📱 Responsive Design

* Works on mobile, tablet, and desktop
* Adaptive layout for smaller screens
* Optimized touch interactions



🛠️ Technologies Used

| Technology              | Purpose                                |
| ----------------------- | -------------------------------------- |
| HTML5                   | Page structure                         |
| CSS3                    | Styling, animations, responsive design |
| JavaScript (Vanilla JS) | Interactivity & DOM manipulation       |
| Google Fonts            | Typography                             |
| Picsum API              | Placeholder images                     |


📂 Project Structure

```
Visuals-Image-Gallery/
│
├── gallery.html      # Main application file
└── README.md         # Project documentation
```

---


## 🎮 Controls

| Action           | Key                  |
| ---------------- | -------------------- |
| Close Lightbox   | ESC                  |
| Next Image       | → Arrow              |
| Previous Image   | ← Arrow              |
| Swipe Navigation | Mobile touch gesture |


💡 How It Works

The gallery images are stored in a JavaScript array:

```js
const images = [
 { id:1, title:"Alpine Solitude", category:"nature", img:"..." }
];
```

JavaScript dynamically:

* Renders images into the DOM
* Filters images by category
* Changes layouts
* Opens a lightbox viewer
* Applies CSS filter effects

No page reloads are needed.

---
 🔮 Future Improvements

* Upload user images
* Search bar
* Download image option
* Favorites/Bookmark system
* Dark/Light theme switch
* Backend storage (Node.js or Firebase)



Give the repository a star!
