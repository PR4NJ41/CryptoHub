# CryptoHub

CryptoHub is a modern web application for cryptocurrency enthusiasts. It provides real-time data, market trends, and user-specific features like watchlists, wallets, and secure transactions.  

Built with ReactJS for a dynamic frontend and Spring Boot for a robust backend, CryptoHub ensures seamless user experiences and top-notch security.

---

## 🚀 Features  
- Real-Time Market Data: Fetch cryptocurrency prices and trends using the CoinGecko API.  
- Secure Transactions: Buy, sell, and transfer cryptocurrencies.  
- Wallet Management: Add funds to wallets or transfer them to a bank account.  
- User Authentication: Powered by JWT and Two-Factor Authentication (2FA).  
- Payment Gateway: Secure payments integrated with Stripe.  
- Responsive UI: Built with ReactJS, optimized for all devices.  

---

## 🛠️ Technologies Used  
- Frontend: ReactJS, CSS  
- Backend: Spring Boot  
- Database: MySQL  
- API Integration: CoinGecko API  
- Authentication: JWT, 2FA  
- Payment Gateway: Stripe  
- Deployment: Dockerized application deployed on AWS EC2  

---

## 🔧 Setup Instructions  

### Prerequisites  
- Node.js and npm installed for frontend.  
- Java and Maven installed for backend.  
- MySQL database set up for data storage.  

### Steps to Run Locally  
1. Clone the Repository:  
  
Bash

   git clone https://github.com/yourusername/CryptoHub.git
   cd CryptoHub
   
2. Setup Frontend:  
  
Bash

   cd Frontend-React
   npm install
   npm start
   
3. Setup Backend:  
   - Update application.properties with your database credentials.  
   - Run the backend:  
    
Bash

     cd Backend
     mvn spring-boot:run
     
4. Access the App:  
   Open http://localhost:5156 in your browser.

---

## 🔒 Security Features  
- JWT Authentication: Ensures secure session management.  
- 2FA: Adds an extra layer of protection for user accounts.  

---

## 📈 API Integration  
- CoinGecko API: Provides real-time market data.  
- Stripe API: Handles secure payment processing.  

---

## 🤝 Contributing  
Contributions are welcome! Feel free to fork this repository and submit pull requests.  
