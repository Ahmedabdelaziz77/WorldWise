# WorldWise - Travel Tracking Application

WorldWise is a travel tracking app that allows users to log the cities and countries they have visited. The app includes a dynamic interface, interactive maps, and comprehensive city and country details.

## Features
### Dynamic Page Navigation
WorldWise provides dynamic navigation, with URLs updating as users move through the app without full page reloads, offering a smooth Single-Page Application (SPA) experience.

### City and Country Lists
The app maintains a list of visited cities and their respective countries, automatically updated based on user input.

### Interactive Maps
An interactive map allows users to view their current location and see cities they've visited as map markers using geolocation APIs.

### City Details
Clicking on a city marker opens detailed information, including the city name, visit date, personal notes, and a link to its Wikipedia page.

### User-Friendly UI
WorldWise has a clean and intuitive interface, making it easy to explore and log travels.

## Tech Stack
- **Vite Integration**: Optimized for fast builds and development, the app uses Vite instead of Create React App.
- **Single-Page Application (SPA)**: SPA architecture allows dynamic content updates without reloading the page.
- **React Components**: Modular React components make the code maintainable and scalable.
- **ESLint**: Integrated to ensure code quality and consistency.
- **React Router**: Provides smooth and dynamic routing for SPAs.
- **createContext and useReducer**: React hooks used to manage state efficiently throughout the application.

## Pages

### Homepage
The landing page introduces the app and includes navigation to the Pricing page, Product page, and Login page.
![1-homePage](https://github.com/user-attachments/assets/6bc38040-ae86-41cd-a49e-8afc5925f758)

### Pricing Page
This page outlines subscription options and features for using the premium version of WorldWise.

### About Page
Provides detailed information about the app, including its purpose, features, and benefits to users.

### Login Page
The login page authenticates users and leads them to the main app once logged in.

## App Pages

### Main App Page
Displays an interactive map showing visited locations. Users can click on map pins to add or update city details, or center the map on their current location.

### Countries Section
Shows a list of all the countries visited, along with relevant statistics and a breakdown of cities visited in each country.

### Add New City Section
Allows users to add a new city by clicking on the map, entering details such as city name, visit date, and personal notes.

## Getting Started
- Clone the repository
- Install dependencies: `npm install`
- Run the app: `npm run dev`

---

This README outlines the core features and structure of WorldWise. For more details on deploying or contributing, consult the full documentation.
