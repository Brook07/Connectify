# 🌐 Connectify

## Location-Based Social Networking Application

This project implements a location-based social networking application that connects users with shared interests, developed as part of the Computer Science (COMP207) course.
Show Image

## 📋 Project Overview
Connectify helps users discover and connect with nearby individuals who share similar interests, fostering meaningful relationships beyond digital interactions.

### Key Features

🗺️ **Location-Based Discovery**: Find users with shared interests in your vicinity
🔍 **Interest Matching**: Smart algorithm for connecting like-minded individuals
💬 **Real-time Chat**: Secure messaging for one-on-one conversations
👥 **Community Groups**: Create or join interest-based local communities
⭐ **Trust System**: Karma-based verification to ensure authentic interactions

### 🛠️ Tech Stack
**Frontend**: React Native for cross-platform mobile development
**Backend**: Node.js with Express.js
**Database**: MongoDB for user profiles and application data
**Authentication**: JWT-based secure authentication
**Real-time Services**: Socket.io for instant messaging
**Location Services**: React Native Geolocation API

### 🚀 Installation
'''bash
# Clone the repository
git clone https://github.com/Brook07/Connectify.git
cd connectify

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env
# Edit .env with your MongoDB connection string and other configs

'''
# Run the application
npm start
📱 App Structure
src/
├── api/            # API connections and services
├── components/     # Reusable UI components
├── contexts/       # React contexts for state management
├── navigation/     # React Navigation setup
├── screens/        # App screens
├── services/       # Business logic and data services
├── utils/          # Helper functions and utilities
└── App.js          # Application entry point

Developed for Kathmandu University, Department of Computer Science and Engineering, 2025
