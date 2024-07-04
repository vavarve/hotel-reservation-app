# Hotel Reservation Management App

## Overview

This is an Angular-based hotel reservation application. It allows users to view, add, update, and delete hotel reservations. The application uses Mockoon as a mock server to simulate HTTP requests and responses without the need for a real backend database.

The purpose of this project is to demonstrate the concepts of Observables and HTTP requests in an Angular application. By using Mockoon, a mock API server, we can simulate the backend interactions required to manage hotel reservations. This project serves as a practical example of how to handle CRUD (Create, Read, Update, Delete) operations in Angular using reactive forms and HTTP client services.

## Features

- **Create and Manage Reservations:** Users can add new reservations with details such as guest name, room type, check-in and check-out dates.
- **Edit Reservations:** Easily edit existing reservations with dynamic form pre-filling.
- **Reactive Forms:** Utilizes Angular's reactive forms with custom validation to ensure data integrity.
- **CRUD Operations:** Seamless integration with backend services to perform create, read, update, and delete operations.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend:**

- Angular
- TypeScript
- Mockoon
- HTML
- CSS

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/vavarve/hotel-reservation-app.git
   cd hotel-reservation-app
   ```

2. **Install dependencies**
   npm install

3.**Run Mockoon mock server**

- Download and install Mockoon from Mockoon's website.
- Start the mock server on port 3001.

  4.**Run Angular Server**

- ng serve
