- # USDC Whale Tracker

## Overview

The **USDC Whale Tracker** is a powerful blockchain monitoring tool designed to track large USDC transactions (whale activity) on the Ethereum network. It categorizes transactions into small, medium, and mega transactions, providing users with real-time insights.

Additionally, the tracker monitors minting and burning events for USDC, offering comprehensive analytics for whale movements and on-chain activity.

## Features

- **Real-time Whale Monitoring**: The tool categorizes transactions based on their size (small, medium, and mega) with real-time updates every 10 seconds.
- **Minting and Burning Events**: It tracks minting and burning events to give users insights into supply changes.
- **Historical Data Analysis**: Whale activity is displayed over time with charts and transaction tables.
- **Vertical Data Separation**: Data is visually distinct with appropriate spacing for improved readability.

## Technologies Used

- **Frontend**: React, Apollo Client, Chart.js
- **Backend**: Graph Protocol Subgraph for Ethereum (USDC)
- **API**: The Graph API for querying blockchain data.

## How to Run the Project Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/WILLFX/USDC-Whale-Tracker.git
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the app:
    ```bash
    npm start
    ```

