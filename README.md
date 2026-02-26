# 🌍 Country Guide App (JavaScript)

A modern, interactive **Country Guide App** built with **JavaScript** that allows users to explore detailed information about countries around the world. The application fetches real-time data from a public API and displays it in a clean and user-friendly interface.

---

## 🚀 Features

- 🔎 Search for any country
- 🌎 View detailed country information:
  - Official Name
  - Capital City
  - Region & Subregion
  - Population
  - Languages
  - Currencies
  - National Flag
- 🗺️ Explore neighboring countries
- 📱 Fully responsive design (Mobile & Desktop)
- ⚡ Fast and lightweight (Vanilla JS)

---

## 🛠️ Built With

- HTML5  
- CSS3  
- JavaScript (ES6+)  
- REST Countries API  

---

## 📂 Project Structure

Country-Guide-App/
│
├── index.html
├── style.css
├── script.js
└── README.md

---

## ⚙️ Installation & Setup

1. Clone the repository

   git clone https://github.com/your-username/country-guide-app.git

2. Navigate into the project directory

   cd country-guide-app

3. Open `index.html` in your browser  

   OR use Live Server (recommended for development)

---

## 🔌 API Integration

This app uses the REST Countries API.

Example endpoint:

https://restcountries.com/v3.1/name/{country}

Example fetch request:

```javascript
fetch(`https://restcountries.com/v3.1/name/${countryName}`)
  .then(response => response.json())
  .then(data => {
    // Process country data here
  })
  .catch(error => console.error("Error fetching data:", error));