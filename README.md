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
![2-pricingPage](https://github.com/user-attachments/assets/18be420f-0a82-4e15-8d68-f282353abc20)

### Product Page
Provides detailed information about the app, including its purpose, features, and benefits to users.
![3-productPage](https://github.com/user-attachments/assets/b359e977-8f41-49a8-a56a-9295e90613ee)

### Login Page
The login page authenticates users and leads them to the main app once logged in.
![4-loginPage](https://github.com/user-attachments/assets/e3b2808c-fa22-4d74-af5e-ffcf872184dd)

## App Pages

### Main App Page
Displays an interactive map showing visited locations. Users can click on map pins to add or update city details, or center the map on their current location.
![5-mainAppPage](https://github.com/user-attachments/assets/8e396443-7407-41aa-b86b-c745aa24eab5)

### Countries Section
Shows a list of all the countries visited, along with relevant statistics and a breakdown of cities visited in each country.
![6-CountriesSection](https://github.com/user-attachments/assets/171cd41f-7698-4e83-8979-d5f391655240)

### Add New City Section
Allows users to add a new city by clicking on the map, entering details such as city name, visit date, and personal notes.
![8-addNewCitySection](https://github.com/user-attachments/assets/7ea7993a-a3ac-4c00-b8e5-47942406d567)

4. **Live Demo**: Includes a link to the live demo. Replace `world-wise-ts.netlify.app/` with the actual URL of your deployed site.

## Getting Started
- Clone the repository
- Install dependencies: `npm install`
- Run the app: `npm run dev`
- Run the server : `npm run server`
---

This README outlines the core features and structure of WorldWise. For more details on deploying or contributing, consult the full documentation.
