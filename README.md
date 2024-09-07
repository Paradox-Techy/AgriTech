# AgriTech

## Overview

AgriTech is a web application designed to predict agri-horticultural commodity prices using advanced data analytics and machine learning techniques. The application features an intuitive interface to visualize data, manage user profiles, and stay updated with real-time notifications and alerts.

## Features

- **Predict Commodity Prices**: View and analyze predictions for various agri-horticultural commodities.
- **Customizable Filters**: Tailor data visualizations and predictions based on your preferences.
- **Data Visualization Tools**: Interactive charts and graphs for better data understanding.
- **Alerts & Notifications**: Receive real-time alerts on price fluctuations and updates.
- **User Profiles**: Manage user settings and preferences for a personalized experience.
- **Search Functionality**: Efficiently search through historical data and market demand.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Dynamic Dashboard**: An interactive dashboard that allows users to explore different decades of price predictions.
- **Real-Time Data Integration**: Seamlessly integrates with real-time data sources for accurate predictions.
- **Error Handling**: Includes error boundaries to manage and display errors gracefully.
- **Lazy Loading**: Utilizes lazy loading for improved performance and faster page loads.

## Technology Stack

- **Frontend**: 
  - React
  - Tailwind CSS
- **Backend**: 
  - Node.js (if applicable, include specifics of backend stack if known)
- **Machine Learning**: 
  - (Specify any libraries or frameworks used if applicable)
- **Routing**: React Router for navigation and lazy loading of components

## Authorship

  - **Developed by**: Vedant Singh
  - **Developed by**: Rishit Vats
  - **Contributed by**: Piyush Saini
  - **Contributed by**: Shaurya Verma 
  - **Contributed by**: Nitin Yadav
  - **Designed by**: Dhriti Mahajan

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
### `src/components/Navbar.jsx`

- **Description**: This React component is the navigation bar for the application. It includes navigation buttons for Home, How It Works, Dashboard, Settings, and a Sign In button.
- **Features**:
  - Navigation buttons with routing functionality
  - Logo display
  - Responsive design

### `src/App.jsx`

- **Description**: This is the main application file that sets up routing for the application. It includes lazy loading for various components and conditional rendering of the Navbar and Footer based on the route.
- **Routes**:
  - `/` - Home
  - `/notification` - Notification
  - `/settings` - Settings
  - `/dashboard` - Dashboard
  - `/how-it-works` - How It Works
  - `/signup` - Sign Up
