# Smart City Parking System

## Project Overview

Smart City Parking System is a mobile application designed to help users find available parking spaces, make reservations, and manage their parking activities.

The project focuses on reliable operation in mobile networks, including situations with unstable connectivity, delayed responses, and temporary network failures.

## Technology Stack

- **Mobile Application:** React Native + TypeScript
- **Backend:** Node.js + TypeScript
- **Database:** MySQL
- **Parking Data Source:** Test data created for the project
- **Communication:** REST API over HTTP

## Main Features

- User registration and login
- Search for nearby parking spaces
- View parking space availability
- Reserve a parking space
- Simulated payments
- Reservation history
- Parking space management by an administrator

## System Architecture

The system consists of three main components:

1. **Mobile Application** - provides the user interface.
2. **Backend Service** - processes requests, validates operations, and manages business logic.
3. **MySQL Database** - stores users, parking spaces, reservations, and simulated payment records.

The mobile application communicates with the backend through a REST API. The backend communicates with the database.

## Network Reliability

The system will address the following network-related challenges:

- Loss of connectivity
- Request timeouts and delayed responses
- Safe retry of requests
- Prevention of duplicate reservations and payments
- Display of cached data with its last update time
- Data synchronisation after connectivity is restored

## Project Goals

The goal is to develop an integrated mobile application, backend service, and database that remain consistent and understandable to users even when network connectivity is unreliable.

## Development Status

Initial project setup and architecture planning.
