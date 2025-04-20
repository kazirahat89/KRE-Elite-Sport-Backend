# KRE Elite Sport Backend

## Project Overview

The KRE Elite Sport Backend is designed to simplify the process of booking sports facilities. This backend application, built using TypeScript, Express.js, and Mongoose, supports essential functionalities like CRUD operations, authentication & authorization, and transaction management. It serves as the backbone for managing facilities, bookings, and user data, ensuring a secure and efficient user experience.

## Features

- **User Authentication & Authorization**:
  - User Sign-Up
  - User Login
  - Role-based Access Control (Admin and User)
- **Facility Management**:
  - Create, Update, and Soft Delete Facilities (Admin Only)
  - Retrieve All Facilities
- **Booking Management**:
  - Check Availability of Facilities
  - Create Bookings (User Only)
  - View All Bookings (Admin Only)
  - View User-specific Bookings (User Only)
  - Cancel Bookings (User Only)
- **Error Handling**:
  - Comprehensive Error Responses
  - Global Error Handling Middleware
- **Validation**:
  - Input validation using Zod
- **Miscellaneous**:
  - Not Found Route Handler
  - Secure Password Handling (Hashing)
  - Transaction & Rollback for Critical Operations

## Technology Stack

- **Programming Language**: TypeScript
- **Web Framework**: Express.js
- **ODM & Validation Library**: Mongoose for MongoDB
- **Validation Library**: Zod

## Live Server

The application is deployed and can be accessed at: [Live Server URL](https://kre-elite-sport-bakend.vercel.app)

## Setting Up and Using the Application

### Prerequisites

- Node.js (>=14.x)
- npm or yarn
- MongoDB

### Installation

1. **Clone the repository**:

   ```sh
   git clone https://github.com/kazirauf/KRE-Elite-Sport-Backend
