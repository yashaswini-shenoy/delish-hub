# Delish Hub

## Project Description

Delish Hub is a full stack MERN project designed as a food ordering platform. The website enables users to register their restaurants, add menus, and manage their offerings. It also allows customers to search, filter, and order food from nearby restaurants. For seamless transactions, a mock payment system is integrated using Stripe. User authentication is securely handled through Auth0. Assets are stored using Cloudinary.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
<!-- - [API Documentation](#api-documentation)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements) -->

## Features

- **User Authentication:** Secure login and registration using Auth0.
- **Restaurant Management:** Users can register restaurants, add menus, and manage orders.
- **Food Ordering:** Customers can search, filter, and order food from nearby restaurants.
- **Payment Integration:** Stripe integration for handling mock payments.
- **Responsive Design:** Optimized for various device sizes.

## Tech Stack

- **Frontend:** React, Tailwind
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Image Storage:** Cloudinary
- **Authentication:** Auth0
- **Payment Integration:** Stripe API
- **Other Tools/Libraries:**
  - dotenv for environment variable management

## Installation

### Prerequisites

- Node.js and npm installed on your local machine
- MongoDB installed and running locally or on a cloud service

### Steps to Run the Project Locally

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yashaswini-shenoy/delish-hub.git
   cd delish-hub
   ```

2. **Setup the backend:**

   ```bash
   cd backend
   ```

   Create the .env file for the environment variables based on the .env.example file. And then run the following commands.

   ```bash
   npm install
   npm run dev
   ```

3. **Setup the frontend:**

   ```bash
   cd frontend
   ```

   Create the .env file for the environment variables based on the .env.example file. And then run the following commands.

   ```bash
   npm install
   npm run dev
   ```

## Usage

### Prerequisites

- Make sure your frontend and backend codes are running. You can access them in their respective port numbers

1. **Access the backend:**
   Use this URL to access your backend locally:

   ```bash
   http://localhost:7000
   ```

2. **Access the frontend:**
   Use this URL to access your frontend locally:

   ```bash
   http://localhost:5173/
   ```
