Zerodha Trading Dashboard Web App
Description
This project simulates a stock trading dashboard inspired by Zerodha, focusing on teaching, virtual trading, and portfolio management using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides essential modules for user authentication, watchlist management, dashboard visualization, and fund transfers. Real trading APIs are not used, making it safe for learning and experimenting
Features
User authentication (login/signup)

Watchlist and portfolio management

Virtual trading (paper trading with simulated money)

Real-time stock data & charting (using Yahoo Finance/API integration)

Clean and responsive UI/UX

Educational components for new traders
Requirements
Node.js and npm

MongoDB instance

React.js (frontend)

Environment variables (.env for API keys)

Internet access for API connections
#Installation
# Clone the repository
git clone https://github.com/rahulxgit/Zerodha.git
cd Zerodha

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Setup environment variables
# Add your MongoDB URI and any API keys to .env in backend

# Start the servers
# Backend
cd ../backend
npm start

# Frontend (in separate terminal)
cd ../frontend
npm start
Usage
Register/login via the web interface.

Create/edit your watchlist.

Access portfolio dashboard for trade simulation.

Explore stock charts and analysis tools.

No real money or trades involved—safe for experiments
Future Scope
Integration with real brokerage APIs for live trading

Mutual funds & SIP options

AI-driven investment suggestions

Advanced analytics & reporting features
