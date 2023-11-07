# Order Delivery Tracking

## Track your Parcels directly here

## Getting Started

This is an order delivery tracking application that simplifies the process of tracking shipments from various delivery partners and comparing prices for pickup orders. This README provides a detailed overview of the project, installation instructions, and usage guidelines.

## Features

- **Unified Tracking Dashboard**: Track orders from multiple delivery partners in one place, eliminating the need to visit multiple websites or apps.

- **Order History**: Keep a comprehensive archive of all your past orders, making it easy to review past deliveries.

- **Real-Time Insights**: Receive real-time updates on estimated delivery times, based on historical data and the latest tracking information.

Before you begin, ensure you have met the following requirements:

- **Node.js**: Install Node.js on your system. You can download it from [nodejs.org](https://nodejs.org/).

- **Git**: You'll need Git for version control. Download it from [git-scm.com](https://git-scm.com/).

### Installation

This project is based on Node.js and helps you track courier services providers in India. You can use this project to build your courier tracking app as it returns the response in JSON format.

### How to Start

- You can download the zip file or clone the repository using Git: `git clone https://github.com/chitra2409/Order-Delivery-Tracking`
- Install all dependencies by running the following command in your terminal: `npm install`
- Start the application using either `yarn start` or `npm start`.
- Open your web browser and visit the URL as mentioned below:

#### Example

If you want to track Ekart with Tracking ID: FMPC0279658213, you can visit the following URL in your browser: `localhost:3000/api/track/ekart/FMPC0279658213`. You will receive a JSON object with all the tracking details.

#### Current Supported Courier Service Providers and Their Endpoints

| Service Providers | Status  |
| :---------------- | :-----: |
| Ekart             | Working |
| Ecom              | Working |
| Delhivery         | Working |
| Xpressbees        |   NA    |
| Bluedart          | Working |
| Gati              |   NA    |
| DTDC              | Working |
| Shadowfax         |   NA    |
| DHL               | Working |
| Maruti(Beta)      | Working |

**Tip**: You can directly insert the tracking ID in the API endpoint instead of `{TrackingId}`.

**Note** : There is a PPT document added in the repository that contained the detailed information about the application

#### API Response Format

If your request is successful, the response will contain three keys: location, detail, and date. See the example below:

```json
{
    "location": "BENGALURU",
    "detail": "Shipment delivered",
    "date": "26 Mar, 2018 12:50 hrs"
}


