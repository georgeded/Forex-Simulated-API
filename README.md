# Forex Simulated API

## Project Overview

The **Forex Simulated API** provides **real-time simulated exchange rates** for a variety of currency pairs, offering both **ask** and **bid** prices. This API is designed for **testing**, **simulation**, and **educational purposes**, mimicking real-world forex market behavior. It's ideal for developers building financial applications, trading algorithms, or for anyone learning about currency markets.

The API is **live** and currently **running on Render**, ensuring continuous performance and availability.

---

## Key Features

- **Dynamic Exchange Rates**: Real-time simulated fluctuations for currency pairs with both **ask** and **bid** prices.
- **Wide Range of Currency Pairs**: Supports a broad selection of currency pairs, including **major** (e.g., USD, EUR, GBP) and **exotic** currencies.
- **RESTful API**: Simple, easy-to-use RESTful API to fetch the latest forex rates.
- **Customizable Price Simulation**: Simulated rates can be adjusted to mimic different market conditions or scenarios for testing trading strategies.
- **Live Deployment on Render**: The API is deployed on **Render**, providing a reliable and scalable environment for real-time usage.

---

## Prerequisites

Before running the API locally or integrating it into your project, ensure you have the following installed:

- **Python 3.x**
- **Flask** for API development
- **Requests** (for testing the API externally)

---

### Forex Rates API

The server provides an endpoint to fetch the latest Forex rates.

- **Endpoint**: `/api/rates`
- **Method**: `GET`
- **Response**:
    ```json
    {
        "currencies": ["USD", "EUR", "GBP", ...],
        "rates": {
            "USD/EUR": 1.1234,
            "EUR/GBP": 0.8765,
            ...
        }
    }
    ```

---
