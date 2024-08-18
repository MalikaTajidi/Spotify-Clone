
# Spotify Features Clone

A web application that incorporates some key features of Spotify, built with the MERN stack:

- **MongoDB**: NoSQL database
- **Express.js**: Web framework for Node.js
- **React.js**: Frontend library
- **Node.js**: JavaScript runtime

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Frontend Setup](#frontend-setup)
- [Backend Setup](#backend-setup)
- [Usage](#usage)


## Overview

This project is a web application that includes some features inspired by Spotify. It uses React.js for the frontend, Node.js and Express.js for the backend, and MongoDB for data storage. The application provides a subset of Spotify-like functionalities, focusing on user experience and music management.

## Features

- **Responsive Design:** Responsive layout with Tailwind CSS for a modern look and feel.
- **Music Player:** Basic controls to play, pause, and skip tracks.
- **Database Integration:** Store playlists, and track information in MongoDB.

## Installation

To set up the project locally, follow these steps:

### **1. Clone the Repository**

```bash
git clone https://github.com/MalikaTajidi/Spotify-Clone.git
```

### **2. Navigate to the Project Directory**

```bash
cd Spotify-Clone
```

## Frontend Setup

### **1. Navigate to the Frontend Directory**

```bash
cd spotify-clone
```

### **2. Install Frontend Dependencies**


```bash
npm install
```

### **3. Set Up Environment Variables**

Create a `.env` file in the `client` directory and add your environment variables. Refer to `.env.example` for sample variables.

## Backend Setup

### **1. Navigate to the Backend Directory**

```bash
cd ../spotify-backend
```

### **2. Install Backend Dependencies**

```bash
npm install
```

### **3. Set Up Environment Variables**

Create a `.env` file in the `server` directory and add your environment variables. Refer to `.env.example` for sample variables.

### **4. Start MongoDB**

Ensure MongoDB is running on your local machine or use a cloud MongoDB service.

## Start the Admin Server

Run the following command to start the admin server:

```bash
npm start
```

This will launch the admin interface, where you can manage songs and albums.

## Usage

### **1. Start the Backend Server**

From the `spotif-backend` directory, run:

```bash
npm start
```

### **2. Start the Frontend Development Server**

From the `spotif-clone` directory, run:

```bash
npm start
```












