# 🌦️ WeatherWise – AI-Powered Weather Forecasting & Insights

WeatherWise is a full-stack weather forecasting application that provides real-time weather updates, hourly forecasts, and 3-day weather predictions. It also integrates a Gemini-powered AI Weather Assistant to provide contextual weather insights.

**🌐 Live Demo:** [WeatherWise](https://weather-forecast-pi-two.vercel.app)

## ✨ Features

- **Real-Time Weather:** Get current weather conditions for searched cities.
- **Hourly Forecast:** View upcoming hourly weather updates.
- **3-Day Forecast:** Explore weather predictions for the next five days.
- **AI Weather Assistant:** Ask weather-related questions using Gemini API.
- **User Authentication:** Secure signup and login using JWT and password hashing.
- **Favourite Cities:** Save and manage your favourite cities.
- **Responsive Design:** Accessible across desktop and mobile devices.
- **Temperature Conversion:** Switch between Celsius and Fahrenheit.

## 🛠️ Tech Stack

**Frontend**
- React.js
- JavaScript
- HTML5
- CSS3
- React Context API

**Backend**
- Node.js
- Express.js
- REST APIs

**Database**
- MongoDB

**APIs & Integration**
- WeatherAPI
- Google Gemini API

**Deployment**
- Vercel (Frontend)
- Render (Backend)

## 📁 Project Structure

```text
WeatherWise/
│
├── public/
├── src/
│   ├── Component/
│   ├── Context/
│   ├── pages/
│   ├── api/
│   ├── App.jsx
│   └── main.jsx
│
├── server/
│   ├── middleware/
│   ├── model/
│   ├── index.js
│   └── package.json
│
├── .gitignore
├── package.json
└── README.md
```

## ⚙️ Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/Sanu0306/Weather-Forecast.git
```

**2. Install frontend dependencies**

bash
cd Weather-Forecast
npm install


**3. Configure frontend environment variables**

Create a `.env` file in the project root:
VITE_API_URL=https://weather-forecast-0at9.onrender.com
VITE_WEATHER_API_KEY=your_weatherapi_key

**4. Start the frontend**

```bash
npm run dev
```

**5. Configure the backend**

Open a new terminal:

```bash
cd server
npm install
```

Create a `.env` file inside the `server` folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

**6. Start the backend**

```bash
npm start
```

## 🚀 Deployment

- Frontend deployed on Vercel.
- Backend deployed on Render.
- Database hosted on MongoDB Atlas.

## 👩‍💻 Developer

**Sangeeta Lowanshi**

- GitHub: [Sanu0306](https://github.com/Sanu0306)
- LinkedIn: [Sangeeta Lowanshi](https://www.linkedin.com/in/sangeeta-lowanshi-78a61a2b8)

---

⭐ If you find this project useful, consider giving it a star!
