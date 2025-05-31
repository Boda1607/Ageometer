# Ageometer
Ageometer is a simple web app that accurately calculates your exact age and lets you choose from 20 themes. It also shares a funny fact about your birthdate, making the experience both personalized and fun.
## Features

- Calculate your exact age (years, months, Weeks, days, Hours, Minutes, Seconds, Femtoseconds).
- Choose from different themes.
- Receive a funny fact related to your birthdate or birth month.
- Clean and minimal design, easy to use.
- Responsive layout — works well on desktop and mobile devices.

## Demo

Check out the live demo here:  
[https://ageometer.netlify.app/](https://ageometer.netlify.app/)

## 📱 iPhone Compatibility

- Optimized for iOS Safari
- Can be **added to the Home Screen** and used like a native app
- Fully functional **offline**
- Supports iOS-style icons and splash behavior

## 🛠️ Tech Stack

- HTML5, CSS3
- JavaScript (ES6+)
- LocalStorage for task persistence
- Web App Manifest for PWA features

## 🌐 Installation (PWA)

1. Open the app in Safari on iPhone
2. Tap **Share > Add to Home Screen**
3. Launch it from the Home Screen like a regular app

## 📁 Project Structure

```bash
├── index.html               # Main app interface
├── manifest.json            # manifest (loaded dynamically)
├── favicon.ico              # App icon
├── 1.png                    # iOS icon
├── service-worker.js        # Enables PWA offline support and caching

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Boda1607/ageometer.git
