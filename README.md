# Fampy – Food Delivery Android App (University Project)

This project is an Android application built to work alongside the Fampy Food Delivery API. It allows users to browse restaurants, select food items, and place orders through a mobile interface.

The app communicates with the backend API to handle authentication, data retrieval, and order processing.

---

## Features

- User registration and login  
- JWT-based authentication (via backend API)  
- Browse restaurants and food items  
- Add items to cart and place orders  
- Location-based ordering using Google Maps  
- View and manage user profile  

---

## Tech Stack

- Java (Android)  
- Android Studio  
- Gson (JSON parsing)  
- HTTP client for API communication  
- Google Maps API  
- REST API integration  

---

## How It Works

- The app connects to the Fampy backend API  
- Users authenticate and receive a token  
- All protected requests include the token  
- JSON data is sent and received using Gson  
- Food, restaurant, and order data are fetched from the API  
- Orders are placed and processed through backend endpoints  

---

## Running the Project

1. Open the project in Android Studio  
2. Make sure the backend API is running locally or hosted  
3. Update the API base URL if needed  
4. Build and run the application on an emulator or physical device  

---

## Notes

This was developed as part of a university project alongside the backend API. It helped me understand mobile development, API integration, and building a full-stack system connecting frontend and backend components.

More recently, I have been focusing on backend and .NET development, building more advanced systems such as real-time applications.
