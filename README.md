# Weather App

A simple weather application that fetches real-time weather data using an API and displays it in a user-friendly interface.

## Features
- **Real-time Weather Data**: Get current weather details based on user location or search input.
- **Responsive Design**: Works on both desktop and mobile devices.
- **API Integration**: Fetches data from a weather API.
- **User-friendly Interface**: Easy-to-use UI for quick weather lookup.

## Prerequisites
Before setting up the project, ensure you have the following installed:

- **Git**: [Download Git](https://git-scm.com/downloads)
- **Node.js** (Latest LTS version): [Download Node.js](https://nodejs.org/)

## Installation
### Step 1: Clone the Repository
```sh
git clone https://github.com/aryan9653/Weather-app.git
cd Weather-app
```

### Step 2: Install Dependencies
```sh
npm install
```

### Step 3: Set Up Environment Variables
Create a `.env` file in the project root and add your API key:
```env
REACT_APP_WEATHER_API_KEY=your_api_key_here
```
Replace `your_api_key_here` with your actual weather API key.

### Step 4: Run the Application
```sh
npm start
```

### Step 5: Access the Application
Once running, open your browser and navigate to:
```
http://localhost:3000
```

## Running with Docker (Optional)
```sh
docker build -t weather-app .
docker run -p 3000:3000 --env-file .env weather-app
```

## Contribution
Feel free to fork the repository, create a new branch, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License.

---


