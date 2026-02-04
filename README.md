# WealthBridge ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Project Description
WealthBridge is a web application designed to empower individual investors by providing personalized investment insights and portfolio management tools. Utilizing AI-driven algorithms, it analyzes user preferences and market trends to suggest optimal investment strategies, ensuring users can make informed decisions in real-time.

## Features
- 🎯 Personalized investment recommendations using AI
- 📈 Real-time portfolio tracking and analysis
- 🔔 Automated rebalancing alerts based on market conditions

## Tech Stack
### Frontend
- **Next.js** 🌐

### Backend
- **FastAPI** 🚀
- **OpenAI Agent SDK** 🤖

### Database
- **PostgreSQL** 🗄️
- **Prisma** 🔗

### Caching
- **Redis** 🧠

## Installation
To set up the project locally, follow these steps:

- Clone the repository
bash
git clone https://github.com/aayush-kumar-codes/wealthbridge-1
- Navigate to the project directory
bash
cd wealthbridge-1
- Install the backend dependencies
bash
cd backend
pip install -r requirements.txt
- Install the frontend dependencies
bash
cd ../frontend
npm install
- Set up the database
bash
npx prisma migrate dev
- Start the backend server
bash
cd ../backend
uvicorn main:app --reload
- Start the frontend server
bash
cd ../frontend
npm run dev
## Usage
Once the application is running, navigate to `http://localhost:3000` in your web browser to access WealthBridge. Create an account or log in to start receiving personalized investment recommendations and track your portfolio.

## API Documentation
For detailed API documentation, please refer to the [API Docs](https://github.com/aayush-kumar-codes/wealthbridge-1/wiki/API-Documentation).

## Testing
To run the tests for the backend, execute the following command:
bash
cd backend
pytest
## Deployment
To deploy WealthBridge, follow these steps:

- Build the frontend for production
bash
cd frontend
npm run build
- Set up a production server (e.g., using Docker or a cloud provider)
- Configure environment variables for database and API keys
- Start the backend server in production mode

## Contributing
We welcome contributions! Please follow these guidelines:

- Fork the repository
- Create a new branch for your feature or bug fix
- Make your changes and commit them
- Push your branch and create a pull request

For more details, please refer to our [CONTRIBUTING.md](https://github.com/aayush-kumar-codes/wealthbridge-1/blob/main/CONTRIBUTING.md). 

Thank you for your interest in WealthBridge! Happy investing! 🚀