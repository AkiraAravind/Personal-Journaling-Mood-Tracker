# Akira Diary Project

**Title:** Akira Diary - Personal Journaling & Mood Tracker
**Description:**
Akira Diary is a web-based personal journaling and mood-tracking app with a beautiful, nature-inspired interface. Users can write notes, track moods, explore inspirational quotes, and customize their experience with themes and backgrounds. The design features animated flowers, butterflies, and a calming color palette, making journaling delightful and mindful.

---

## Project Overview
Akira Diary is a React-based web app designed for personal journaling, mood tracking, and inspiration. The app is visually rich, with animated elements and a calming UI. It is structured for easy conversion to mobile or desktop platforms (PWA/React Native).

## Main Concepts & Components

### 1. App.js
- **Purpose:** Main entry point, handles routing and splash/intro logic.
- **Role:** Root navigator in mobile/desktop versions.

### 2. Intro.js
- **Purpose:** Animated intro screen with butterflies, flowers, and title animation.
- **Role:** Sets a calming mood as the splash screen.

### 3. Layout.js
- **Purpose:** Main layout, header, navigation drawer, and bottom navigation bar.
- **Role:** Persistent navigation in all app views.

### 4. Home.js
- **Purpose:** Welcome page with a call to action (“Get Started”).
- **Role:** Landing page after splash, introduces app purpose.

### 5. Notes.js, NoteDetail.js, NoteNew.js, NoteEdit.js
- **Purpose:** Create, view, edit, and manage journal entries. Includes mood tracking and background customization.
- **Role:** Core journaling functionality.

### 6. Explore.js
- **Purpose:** Searchable list of inspirational quotes, categorized by theme.
- **Role:** Discover/inspiration tab.

### 7. Calendar.js
- **Purpose:** Calendar view with mood and note indicators.
- **Role:** Visualizes journaling activity and moods over time.

### 8. Settings.js
- **Purpose:** Customization options (themes, fonts, dark mode, etc.).
- **Role:** Personalizes user experience.

## Design & Experience
- Animated butterflies, flowers, and pastel gradients for a tranquil atmosphere.
- Responsive design for web and mobile.
- Easy navigation and intuitive UI.

## Technologies Used
- React, Tailwind CSS, PostCSS
- Context API for state management
- PWA-ready structure

## Folder Structure
- `src/` - Main React app source code
- `public/` - Static assets and HTML
- `app-design/` - UI/UX concepts and HTML mockups
- `server/` - Backend server (if needed)

## Getting Started
1. Install dependencies: `npm install`
2. Start the app: `npm start`
3. Explore features and customize your journaling experience!

---

For more details, see individual component files and the `app-design` folder for UI/UX concepts.
