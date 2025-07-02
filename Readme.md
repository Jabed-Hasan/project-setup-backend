#  Backend Setup

A backend system for managing  operations built with Node.js, Express, and MongoDB.

## Overview

This project serves as the backend API for a management system, handling data operations for functions.

## Technologies Used

- Node.js
- Express.js
- MongoDB with Mongoose
- TypeScript

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Jabed-Hasan/project-setup-backend.git
   cd project-setup-backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with the following variables:
   ```
   PORT=5000
   DATABASE_URL=mongodb://localhost:27017/management
   ```

### Running the Application

Development mode:
```bash
npm run start:dev
```

Production build:
```bash
npm run build
npm run start:prod
```

## Project Structure 
