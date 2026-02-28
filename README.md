# SmartGarden-AI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview

SmartGarden-AI is an innovative project designed to help plant enthusiasts and gardeners optimize their plant care using artificial intelligence. It leverages real-time sensor data to monitor soil moisture, temperature, and light, providing actionable insights to maintain a healthy garden effortlessly.

## Features

- Real-time monitoring of soil moisture, temperature, and light levels.
- AI-powered recommendations for watering and plant care.
- Mobile-friendly web dashboard with intuitive UI.
- Customizable alerts and notifications.
- Historical data visualization to track plant growth and health.

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express
- **AI/ML:** Python with TensorFlow
- **Database:** MongoDB
- **IoT:** Arduino sensors for soil moisture, temperature, and light

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/arderentoggje/SmartGarden-AI.git
   ```
2. Navigate to the project directory:
   ```
   cd SmartGarden-AI
   ```
3. Install backend dependencies:
   ```
   cd backend
   npm install
   ```
4. Install frontend dependencies:
   ```
   cd ../frontend
   npm install
   ```
5. Set up your environment variables (refer to `.env.example` files).
6. Connect your IoT sensors to the backend.

## Usage

- Start the backend server:
  ```
  cd backend
  npm start
  ```
- Start the frontend server:
  ```
  cd ../frontend
  npm start
  ```
- Access the dashboard at `http://localhost:3000`.
- Add your plants and configure sensor thresholds.
- Monitor real-time data and receive AI-driven care tips.

## Screenshots

![Dashboard Overview](https://via.placeholder.com/800x400.png?text=Dashboard+Overview)

![Real-time Monitoring](https://via.placeholder.com/800x400.png?text=Real-time+Monitoring)

![AI Recommendations](https://via.placeholder.com/800x400.png?text=AI+Recommendations)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository on GitHub: [arderentoggje/SmartGarden-AI](https://github.com/arderentoggje/SmartGarden-AI)
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

Please ensure your code adheres to the existing style and includes relevant tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Author

[arderentoggje](https://github.com/arderentoggje) - passionate developer focused on IoT and AI integration.
