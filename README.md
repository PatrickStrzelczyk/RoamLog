# RoamLog
A mobile-first Progressive Web App travel journal for capturing and storing travel memories offline.


# RoamLog 📍

**A personal travel journal Progressive Web Application (PWA).**

RoamLog is a mobile-first travel journal that allows users to capture, save, and revisit their travel memories. Users can create journal entries containing photographs, descriptions, dates, and geographical locations.

The application is designed to work offline, allowing users to access their saved memories without an internet connection.

## ✨ Features

- Create and manage travel memories.
- Add photographs from the device camera or gallery.
- Attach geographical coordinates using GPS.
- View, edit, and delete journal entries.
- Store memories locally using IndexedDB.
- Access saved memories offline.
- Install the application on supported mobile devices.
- Responsive design for mobile, tablet, and desktop.

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- IndexedDB
- Service Workers
- Cache API
- Web App Manifest
- Geolocation API
- Camera / File Input API

## 📱 Application Views

1. **Journal:** Browse saved travel memories.
2. **Add Memory:** Create a new journal entry.
3. **Memory Details:** View, edit, or delete an existing entry.

## 📡 Offline Functionality

RoamLog uses a service worker to cache essential application resources and IndexedDB to store user-created memories and photographs.

The application aims to provide access to saved memories and core functionality without an internet connection.

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the project in Visual Studio Code.
3. Run the application using a local development server, such as the Live Server extension.
4. Open the application in your browser.

Camera, geolocation, service workers, and installation features require a secure context (HTTPS or localhost).

## 🌐 Live Application

Coming soon.

## 📂 Project Structure

```text
roamlog/
├── index.html
├── manifest.json
├── sw.js
├── README.md
├── .gitignore
├── css/
├── js/
├── assets/
└── screenshots/
```

## 📖 Project Purpose

This project is being developed as part of the Progressive Mobile Applications course.

The objective is to demonstrate the development of an installable, responsive, and offline-capable Progressive Web Application using standard web technologies.

## 🔮 Future Improvements

- Interactive map displaying saved memories.
- Travel statistics and visited places.
- Cloud backup and synchronisation.
- Sharing travel memories with others.

---

**Project:** RoamLog  
**Type:** Progressive Web Application (PWA)  
**Status:** In Development
