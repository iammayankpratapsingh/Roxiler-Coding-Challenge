# Project Name

## Description

This project is a dashboard application built with React and Ant Design for the frontend, and a Node.js backend connected to MongoDB for data storage. It allows users to view transactions and statistics based on a selected month.

## Prerequisites

Before you can run the project locally, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (preferably the latest stable version)
- [npm](https://www.npmjs.com/) (Node package manager)
- [MongoDB](https://www.mongodb.com/) (If you are using a local MongoDB instance)

## Setup Instructions

### Update MongoDB URI

Before running the project, update the MongoDB URI in the backend configuration.

1. **Locate the MongoDB URI in the backend:**
   - Open the backend folder.
   - Find the file that contains the MongoDB URI (likely `config.js` or `db.js`).
   - Replace the URI with your MongoDB connection string (e.g., `mongodb://localhost:27017/your-database-name`).

### Install Dependencies

1. **Install dependencies in the frontend:**
   - Navigate to the `frontend` directory.
   - Run the following command to install the necessary packages:
   ```bash
   npm install
