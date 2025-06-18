## 🖼️ Modal Image Gallery

Welcome to my interactive **Modal Image Gallery** project! This simple yet elegant web application allows users to view cat images in a full-screen modal view when clicked—perfect for showcasing UI/UX functionality using pure HTML, CSS, and JavaScript.

## 🍿 Credits and to copy and bash
https://github.com/Fahim-Dot-Com/MyArtGallery/edit/main/README.md

## 🚀 Live Demo
🌐 [View the project live]
coming soon!

## 📸 Preview
Mimo IDE
![Screenshot_20250618_185953_Mimo](https://github.com/user-attachments/assets/b43dc55f-3fa2-4a45-ab20-aff8e63cb125)

The gallery features:
- 🐾 Whispurr
- 🐾 Babaganoosh
- 🐾 Nacho

## 🛠️ Tech Stack
- **HTML** – Semantic structure and layout
- **CSS** – Styling with hover animations and responsive layout using Flexbox
- **JavaScript** – Dynamic modal functionality

## 🧠 Features
- 🖱️ Clickable thumbnails that open full-size images in a modal
- ❌ Modal close button for a smooth user experience
- ✨ Subtle hover animations on images
- 📱 Responsive design with flexible layout

## 🧾 Code Overview

### index.html
Contains:
- Page layout
- Image thumbnails
- Modal container for image display

### style.css
Controls:
- Page layout and text alignment
- Image styling with hover effects
- Modal design with overlay and centering logic

### script.js
Handles:
- Modal open on image click
- Modal close logic

```javascript
function showModal(thumbnail) {
  modal.style.display = "block";
  modalContent.src = thumbnail.src;
}
function hideModal() {
  modal.style.display = "none";
}
