# Parcel-Tracker-Site

# 📦 YellowTrack – Parcel Tracking App

A professional, scalable, and user-friendly parcel tracking web app built with ReactJS. Created as part of a technical evaluation for Yellow Corporation.

---

## 🧠 UX Philosophy

This project applies modern design and psychology principles to build trust and clarity for users tracking their parcels:

- 🎯 Swiss Grid system for structured visual hierarchy
- 🎨 Emotionally responsive color palette tied to parcel status
- 🧠 NLP & Priming for comfort and control
- 📱 Responsive design for mobile & desktop

---

## 🚀 Features

- 📋 View list of orders with:
  - Displays ETA, status, pickup location
  - Live-translated content (EN/SV toggle)
  - Status badge with color-coded meaning
- 🔍 Order detail page:
  - Extended info (delivery address, user name, parcel ID)
  - Live interactive map with parcel coordinates
- 🌐 i18n support via Context + custom translation structure
- Language toggle (English / Swedish)
- ⚠️ Graceful 404 fallback page
- 💬 Fully scalable for future language and region support

---

## 🛠 Tech Stack

- React (CRA)
- Styled-components
- Axios (API calls)
- React Router v6
- React Context (for i18n prep)
- Leaflet + OpenStreetMap (interactive maps)
- Mockaroo (for order data)

---

## 📦 Installation

```bash
git clone https://github.com/anonManBond/Parcel-Tracker-Site.git
cd Parcel-Tracker-Site
npm install
npm start

---

## 🗺 Live Map Note
 Due to API quota limits on Mockaroo, data has been cached locally during development (/public/mock-orders.json).
 Map coordinates are resolved using OpenStreetMap Nominatim API or directly from location_coordinate_latitude/longitude fields provided in the dataset.

