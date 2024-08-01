# CODTECH-task-2
Name: KIRTHIKA S 
Company: CODTECH IT SOLUTIONS 
ID: CT4AD4637 
Domain: ANDROID DEVELOPMENT 
Duration: JULY TO AUGUST 2024 Mentor: NEELA SANTHOSH KUMAR

# Overview of the project

# Project: WEATHER REPORT APP

![Weather report op](https://github.com/user-attachments/assets/0703dce9-bfe8-4016-b10b-e7d44f4be9bc)

# Objective
Educational Purpose: Provide a basic understanding of Flutter application development.
User Interface Experience: Allow users to input a city name and display corresponding weather information.
Simulation of Network Operations: Simulate network requests to demonstrate asynchronous programming and state management in Flutter.

# Key Activities
Application Setup:
Initialize a new Flutter project.
Configure project dependencies.
Service Implementation:
Create a service (WeatherService) to fetch or simulate weather data.
UI Development:
Design a simple user interface with a text field for city input and a button to fetch weather data.
Display the weather information on the screen.
State Management:
Manage the state of the weather data and user input within the app.
Simulated Data Handling:
Simulate network latency and response for educational purposes.

# Technologies Used
Flutter:
Framework: Flutter SDK for building the user interface.
Widgets: MaterialApp, StatelessWidget, StatefulWidget, TextField, ElevatedButton, and Scaffold for UI components.
Dart:
Language: Dart programming language for writing the app logic and UI.
Asynchronous Programming: Use of Future and async/await for handling asynchronous operations.

# Detailed Breakdown
Application Setup
Objective: Set up a new Flutter project with necessary configurations.
Activities:
Create a new Flutter project using flutter create weather_app.
Configure pubspec.yaml for dependencies.
2. Service Implementation
Objective: Simulate fetching weather data.
Activities:
Create WeatherService class in lib/services/weather_service.dart.
Implement a method fetchWeather that simulates network latency and returns hardcoded weather data.
3. UI Development
Objective: Design and implement the user interface.
Activities:
Create MyApp and WeatherScreen widgets in lib/main.dart.
Implement a text field for city input and a button to trigger the weather data fetch.
Display the fetched weather data using Text widgets.
4. State Management
Objective: Manage the application state effectively.
Activities:
Use a StatefulWidget to manage the state of the city input and fetched weather data.
Update the UI based on the state changes.
5. Simulated Data Handling
Objective: Simulate network operations for educational purposes.
Activities:
Add a delay in the fetchWeather method to simulate network latency.
Return hardcoded weather data after the delay to simulate a network response.
