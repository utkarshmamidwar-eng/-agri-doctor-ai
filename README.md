
<div align="center">

# 🌱 AgriDoctor

### Smart Agricultural Assistance for Every Farmer

A multilingual agricultural assistance web application prototype for exploring crop health information, preliminary disease suggestions and weather-based farming guidance.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Project Status](https://img.shields.io/badge/Status-Prototype-orange?style=for-the-badge)

**Learn 🌿 | Explore 🌾 | Innovate 🚀**

[View Repository](https://github.com/utkarshmamidwar-eng/Agri-Doctor-)

</div>

---

## 📖 About AgriDoctor

AgriDoctor is a web-based agricultural assistance project designed to make basic crop-health information and agricultural guidance more accessible.

The application provides an interactive interface where users can upload plant leaf images, explore preliminary crop disease suggestions, access weather information and interact with a keyword-based agricultural assistant.

The platform is designed with multilingual accessibility, supporting:

- 🇬🇧 English
- 🇮🇳 Hindi
- 🌾 Marathi

## 🎯 Problem Statement

Farmers may face challenges accessing understandable digital resources about crop health, weather conditions and agricultural practices.

AgriDoctor explores how simple web technologies can make agricultural information easier to access through a user-friendly digital platform.

## ✨ Features

### 🌿 1. Crop Health Assistance
- Upload plant leaf images using a camera or gallery.
- Drag-and-drop image upload.
- Crop-name-based disease suggestions.
- Built-in crop and disease reference catalogue.
- Preliminary disease information and symptoms.

### 🤖 2. Agricultural Chat Assistant
- Offline keyword-based responses.
- Crop disease information.
- Basic treatment and prevention guidance.
- Suggested agricultural questions.

### 🌦️ 3. Weather Information
- Browser-based location detection.
- Current temperature and humidity.
- Wind speed and weather conditions.
- Basic weather-based farming guidance.
- Approximate location fallback.

### 🌐 4. Multilingual Interface
- English language support.
- Hindi language support.
- Marathi language support.

### 👨‍🌾 5. Farmer Profile
- Enter user name and mobile number.
- Continue as a guest.
- Edit profile information.
- Add primary crop information.

### 📋 6. Scan History
- View recent scan results.
- Explore previously displayed disease information.
- View scan statistics during the current session.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Responsive design and styling |
| JavaScript | Application functionality |
| Open-Meteo API | Weather information |
| Nominatim API | Reverse geocoding |
| Browser Geolocation API | Location detection |
| IPAPI | Approximate location fallback |

## ⚙️ How It Works

The current prototype follows a rule-based approach.

1. User opens the AgriDoctor application.
2. User selects a preferred language.
3. User enters profile details or continues as a guest.
4. User uploads a plant leaf image.
5. JavaScript checks the image filename and available crop information against predefined keywords.
6. The application displays a matching crop or disease reference where available.
7. Users can explore symptoms, preliminary treatment information and prevention tips.

**Important:** The current prototype does not analyse image pixels using a trained machine-learning model. Its disease suggestions are based on filename and crop-name keyword matching. The chat assistant also uses predefined keyword-based responses rather than a live AI model.

## 🚀 Getting Started

### Prerequisites

- A modern web browser.
- Visual Studio Code (recommended).
- Internet connection for external weather and location services.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/utkarshmamidwar-eng/Agri-Doctor-.git
```

**2. Open the project folder**

```bash
cd Agri-Doctor-
```

**3. Open the application**

The current application is provided as a standalone HTML file.

Open `#AgriDoctor AI.html` in your browser.

For cleaner project organization, you can rename the file to `index.html` before deployment.

Alternatively, open the project in VS Code and use the Live Server extension.

## 📸 Screenshots

Add screenshots of your actual application in this section.

Suggested screenshots:

- Application homepage
- Login and language selection
- Leaf upload interface
- Crop-health results
- Weather dashboard
- Agricultural chat assistant

Example:

```markdown
![AgriDoctor Homepage](assets/screenshots/homepage.png)

![Crop Scan Interface](assets/screenshots/scan.png)

![Weather Dashboard](assets/screenshots/weather.png)
```

## 📂 Project Structure

Current prototype:

```text
AgriDoctor/
│
├── #AgriDoctor AI.html
└── README.md
```

Suggested future organization:

```text
AgriDoctor/
│
├── index.html
├── assets/
│   ├── images/
│   └── screenshots/
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   ├── disease-data.js
│   └── translations.js
│
└── README.md
```

## 🔮 Future Roadmap

- [ ] Actual AI-powered crop disease image classification.
- [ ] Integration of a trained machine-learning model.
- [ ] Improved crop disease reference database.
- [ ] Verified agricultural knowledge resources.
- [ ] More Indian regional languages.
- [ ] Real-time weather alerts.
- [ ] Secure user authentication.
- [ ] Persistent scan history and downloadable reports.
- [ ] Mobile-friendly Progressive Web App.
- [ ] Improved farmer dashboard.

## ⚠️ Limitations & Disclaimer

AgriDoctor is an educational prototype and should not be considered a professional crop diagnosis system.

- Disease suggestions are based on predefined keyword matching.
- Uploaded images are not analysed by a trained image-recognition model.
- Chat responses are keyword-based and offline.
- User profiles and scan history are maintained in application memory and are not stored in a backend database.
- Weather information requires external services and an internet connection.
- Treatment information is preliminary and must be verified with qualified agricultural experts.

Do not use pesticide or fungicide recommendations without checking the product label, local regulations and expert guidance.

## 🤝 Future Contributions

Suggestions and improvements are welcome.

1. Fork this repository.
2. Create a new branch.
3. Implement your improvements.
4. Submit a Pull Request.

## 👨‍💻 Developer

**Utkarsh Mamidwar**

Computer Engineering Student  
Jagadambha College of Engineering & Technology (JCOET), Yavatmal.

- GitHub: [@utkarshmamidwar-eng](https://github.com/utkarshmamidwar-eng)
- Project: [AgriDoctor](https://github.com/utkarshmamidwar-eng/Agri-Doctor-)

---

<div align="center">

### 🌱 Technology for Agriculture. Innovation for Farmers.

**Built with curiosity, creativity and code.**

⭐ If you find this project interesting, consider giving it a star!

</div>
