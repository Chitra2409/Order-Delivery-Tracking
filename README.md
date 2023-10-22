# Order Delivery Tracking

## Track your Parcels directly here

## Getting Started

This is an order delivery tracking application that simplifies the process of tracking shipments from various delivery partners and comparing prices for pickup orders. This README provides a detailed overview of the project, installation instructions, and usage guidelines.

## Features

- **Unified Tracking Dashboard**: Track orders from multiple delivery partners in one place, eliminating the need to visit multiple websites or apps.

- **Order History**: Keep a comprehensive archive of all your past orders, making it easy to review past deliveries.


Before you begin, ensure you have met the following requirements:

- **Node.js**: Install Node.js on your system. You can download it from [nodejs.org](https://nodejs.org/).

- **Git**: You'll need Git for version control. Download it from [git-scm.com](https://git-scm.com/).

### Installation

This project is based on nodejs help to track the courier servies provider in India.

You can use this project to build your courier tracking app as it return the response in json format.

### How to Start

-->You can download zip or git clone https://github.com/chitra2409/Order-Delivery-Tracking

-->You can install all dependency by running command on bash(Terminal): npm install

-->Then run: yarn start or npm start

-->Then Open Browser and hit url mentioned below like

###### Example

If You want to track Ekart with Tracking Id: FMPC0279658213 then in chrome visit url localhost:3000/api/track/ekart/FMPC0279658213

And then you will get Json Object with all tracking Details

#### Current Supported Courier service and their endpoints

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

###### Tip: Directly insert tracking id in api end point instead of {TrackingId}

###### API Respone Format

If your request is successfull then response will contain three keys i.e. location, detail, date.
Check the example below.

Example

```
    {
        "location": "BENGALURU",
        "detail": "Shipment delivered",
        "date": "26 Mar, 2018 12:50 hrs"
    },
```




