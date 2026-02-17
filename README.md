# MediSlot Mobile App

[![Stack](https://img.shields.io/badge/Stack-React%20Native%20%2B%20Express-0ea5e9)](#tech-stack)
[![Mobile](https://img.shields.io/badge/Mobile-Expo-000020)](#tech-stack)
[![Backend](https://img.shields.io/badge/Backend-Node.js-3c873a)](#tech-stack)
[![Database](https://img.shields.io/badge/Database-MongoDB-4ea94b)](#tech-stack)

A mobile-first healthcare booking platform to discover health centers, book tests, track appointments, and access health guidance.

## Screenshots

### Home
![Home](docs/screenshots/home.png)

### Health Awareness Feed
![Health Awareness Feed](docs/screenshots/health-awareness-feed.png)

### Multi-language Guidelines
![Multi-language Guidelines](docs/screenshots/Multilanguage.png)

### Health Centers Map
![Health Centers Map](docs/screenshots/health-centers-map.png)

### Book New Test
![Book New Test](docs/screenshots/book-new-test.png)

### My Checklist
![My Checklist](docs/screenshots/my-checklist.png)

## Features

- Real-time diagnostic test booking
- Health center map view
- Payment options (online or pay at center)
- Booking and report verification flow
- Booking history and personal checklist
- Health awareness and guideline content
- Sinhala and English language support

## Tech Stack

- Mobile: React Native, Expo
- Backend: Node.js, Express.js, Mongoose
- Database: MongoDB
- Web (optional module): React + Vite

## Quick Start

### 1) Backend

```bash
cd Backend
npm install
npm run dev
```

### 2) Mobile App (Expo)

```bash
cd MediSlotApp
npm install
npm start
```

### 3) Web App (Optional)

```bash
cd web
npm install
npm run dev
```

## Environment (`Backend/.env`)

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/medislot
```

Add any additional keys your local setup requires.

## Project Structure

```text
medislot-mobileApp/
  Backend/
  MediSlotApp/
  web/
  docs/
    screenshots/
```

## License

For academic/project use. Add a formal license (for example, MIT) if needed.
