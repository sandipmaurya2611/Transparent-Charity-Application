# Transparent Charity Application

This project is a transparent charity application built using blockchain technology. The goal is to provide a secure and transparent platform for donations, ensuring that funds reach their intended recipients without any misappropriation.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Transparent Charity Application leverages blockchain technology to provide a secure and transparent method for handling donations. By using blockchain, every transaction is recorded in a public ledger, ensuring that all donations are traceable and tamper-proof. This enhances trust and accountability in the charitable sector.

## Features

- **Secure Transactions**: All donations are processed through blockchain, ensuring security and transparency.
- **Traceability**: Donors can track their donations and see exactly how their funds are being used.
- **Smart Contracts**: Automated smart contracts manage the distribution of funds, ensuring they are used as intended.
- **User Authentication**: Secure login and registration for donors and charity organizations.
- **Dashboard**: A user-friendly dashboard for donors to view their donation history and for charities to manage their received funds.

## Technologies Used

- **Frontend**: React, HTML, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Blockchain**: Ethereum, Solidity
- **Database**: MongoDB
- **Smart Contracts**: Solidity

## Prerequisites

- Node.js and npm installed
- MongoDB installed and running
- Ethereum Wallet (e.g., MetaMask) for handling transactions

## Installation

### Backend Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/transparent-charity.git
    cd transparent-charity/backend
    ```

2. Install backend dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the backend directory and add your MongoDB connection string and other environment variables:

    ```env
    MONGODB_URI=mongodb://localhost:27017/charity
    JWT_SECRET=your_jwt_secret
    ```

4. Start the backend server:

    ```bash
    npm start
    ```

### Frontend Setup

1. Navigate to the `frontend` directory:

    ```bash
    cd ../frontend
    ```

2. Install frontend dependencies:

    ```bash
    npm install
    ```

3. Start the frontend development server:

    ```bash
    npm start
    ```

### Smart Contracts Setup

1. Navigate to the `contracts` directory:

    ```bash
    cd ../contracts
    ```

2. Install Truffle and Ganache CLI globally if not already installed:

    ```bash
    npm install -g truffle ganache-cli
    ```

3. Compile the smart contracts:

    ```bash
    truffle compile
    ```

4. Migrate the smart contracts to the blockchain:

    ```bash
    truffle migrate
    ```

## Usage

1. Open the frontend in your web browser.
2. Register or log in as a donor or charity organization.
3. Donors can make donations using their Ethereum wallet.
4. Track donations and view fund usage through the dashboard.

## Project Structure

```plaintext
├── backend/
│   ├── controllers/        # Controllers for handling requests
│   ├── models/             # Mongoose models
│   ├── routes/             # Express routes
│   ├── middleware/         # Custom middleware
│   ├── utils/              # Utility functions
│   ├── .env                # Environment variables
│   ├── server.js           # Main server file
├── frontend/
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── pages/          # React pages
│   │   ├── services/       # Services for API calls
│   │   ├── App.js          # Main App component
│   │   ├── index.js        # Entry point
│   ├── public/             # Public assets
│   ├── tailwind.config.js  # Tailwind CSS configuration
│   ├── package.json        # Frontend dependencies
├── contracts/
│   ├── migrations/         # Migration scripts
│   ├── contracts/          # Solidity smart contracts
│   ├── test/               # Smart contract tests
│   ├── truffle-config.js   # Truffle configuration
├── README.md               # Project documentation

Contributing
Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcomed.

Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.
