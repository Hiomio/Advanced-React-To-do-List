<div align="center">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="100"/>
</div>

# 📝 Advanced React To-Do Application with Weather Integration

> **Enhancing Productivity with Real-Time Weather Updates**

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=4000&pause=1000&color=4CAF50&center=true&vCenter=true&width=435&lines=Advanced+To-Do+App+with+Weather+Integration;Built+with+React+%7C+Redux+%7C+Material-UI;Responsive+and+User-Friendly+Design" />
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/React-%E2%9C%93-61DAFB" />
  <img src="https://img.shields.io/badge/Redux-%E2%9C%93-764ABC" />
  <img src="https://img.shields.io/badge/Material--UI-%E2%9C%93-0081CB" />
  <img src="https://img.shields.io/badge/JavaScript-%E2%9C%93-F7DF1E" />
  <img src="https://img.shields.io/badge/HTML5-%E2%9C%93-E34F26" />
  <img src="https://img.shields.io/badge/CSS3-%E2%9C%93-1572B6" />
  <img src="https://img.shields.io/badge/Weather%20API-%E2%9C%93-1E90FF" />
</p>

---

## 🌟 Project Overview

The **Advanced React To-Do Application with Weather Integration** is a feature-rich task management tool designed to enhance productivity. By integrating real-time weather data using the OpenWeatherMap API, this application offers users contextual information, allowing them to plan tasks more effectively based on current weather conditions.

## 🚀 Features

- **Task Management**: Add, view, edit, and delete tasks effortlessly.
- **Task Prioritization**: Assign priorities (High, Medium, Low) to tasks for better organization.
- **Weather Integration**: Fetch and display current weather conditions for task locations using the OpenWeatherMap API.
- **User Authentication**: Secure login and logout functionalities using mock authentication.
- **Persistent Storage**: Tasks and authentication status are saved using local storage, ensuring data persistence across sessions.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices using Material-UI's responsive grid system.

---

## 🖼️ Screenshots

### 🏠 Home Page
<p align="center">
  <img src="screenshots/home 1.png" alt="Home Page" width="800"/>
</p>


### ➕ Add Task
<p align="center">
  <img src="./screenshots/Add Task.png" alt="Add Task" width="800"/>
</p>

<p align="center">
  <img src="./screenshots/Add Task 2.png" alt="Add Task" width="800"/>
</p>

### 🌤️ Weather Integration
<p align="center">
  <img src="./screenshots/Weather API Integration.png" alt="Weather Integration" width="800"/>
</p>

### 🔑 User Authentication
<p align="center">
  <img src="./screenshots/Signin.png" alt="User Authentication" width="800"/>
</p>

#### 📱 Mobile View
<p align="center">
  <img src="screenshots/desktop.jpeg" alt="SignIn Page Mobile View" width="400"/>
</p>

<p align="center">
  <img src="screenshots/desktop 1.jpeg" alt="Home Page Mobile View" width="400"/>
</p>


## 🛠️ Technologies Used

| Technology | Description |
|------------|-------------|
| ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react) | JavaScript library for building user interfaces |
| ![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux) | State management library |
| ![Material-UI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui) | React UI framework for responsive and modern design |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript) | Programming language for web development |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5) | Markup language for structuring web content |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3) | Style sheet language for designing web pages |
| ![Weather API](https://img.shields.io/badge/Weather%20API-1E90FF?style=for-the-badge&logo=openweathermap) | API for accessing current weather data |

## **Setup Instructions**

1. **Prerequisites**
   - Node.js (v16 or later) and npm installed.
   - A Weather API key from WeatherAPI.

2. **Clone the Repository**
git clone  
https://github.com/abhijit2607/Advanced-React-To-do-App   
cd advanced-react-todo-app

3. **Create React App**
If the repository does not include pre-initialized React files, initialize a new React app:  
npx create-react-app

4. **Install Dependencies**  
npm install


5. **Update API Key**  
Update the API key in the services/api.js file
API Integration**: Weather API ([weatherapi.com](https://www.weatherapi.com/))


7. **Start the Development Server**  
npm start

The application will run at [http://localhost:3000](http://localhost:3000).

---

### **Running Tests**
To run tests (if applicable), use the following command:  
npm test


---

### **Features Breakdown**

#### To-Do Features
- Add new tasks via an input field with priority selection.
- Delete tasks directly from the task list.
- View active and completed tasks in separate sections.
- Persistent storage ensures tasks remain saved across sessions.

#### Weather Widget
- Automatically detects the user's location and fetches a 3-day weather forecast.
- Users can search for the weather in other cities.
- Displays temperature, weather conditions, and city details.

#### Responsive Design
- Fully responsive layout using Tailwind CSS, with a mobile-first approach.
- Optimized for all device sizes (mobile, tablet, laptop, desktop).

#### State Management
- Redux Toolkit manages application state.
- Redux Thunk handles asynchronous actions like API calls for weather data.

#### Authentication
- Mock login/logout system implemented using Redux.
- Protects the To-Do list, ensuring only authenticated users can access tasks.

---

### **Usage**

#### Tasks
- Add, delete, and prioritize tasks.
- Toggle between active and completed tasks.

#### Weather Widget
- View the weather forecast for your location or any city.

#### Authentication
- Login to access and manage tasks. Logout to secure your session.

---
> **Note:** Credentials for mock authentication:  
Email= user@example.com  
password= password123

---

---

