# 📈 CryptoTracker – iOS App

An iOS application that fetches **real-time cryptocurrency market data** using the [CoinGecko API](https://www.coingecko.com/en/api).  
This project demonstrates my **networking skills in iOS** (API integration, JSON parsing, async handling) and also showcases **backend handling skills** such as data caching, error handling, and clean architecture.

---

## 📸 Screenshots  

<p align="center">
  <img width="1470" height="956" alt="Screenshot 2025-10-03 at 10 13 58 AM" src="https://github.com/user-attachments/assets/c198512a-8e2e-45ac-afcd-3ed8932166bd" />
</p>

---

## 🚀 Features
- Fetch live data from the **CoinGecko API**.  
- Display **top cryptocurrencies** with price, market cap, and daily changes.  
- Detailed screen with coin info, 24h price chart, and percentage change.  
- Implements **async/await** for networking.  
- **Error handling & retry mechanism** for failed API calls.  
- **Caching layer** to minimize API calls and improve performance.  
- Built with **MVVM architecture** for clean separation of concerns.  

---

## 🛠 Technical Skills Demonstrated
- **Networking in iOS**:
  - `URLSession` with async/await.  
  - Codable models for parsing JSON.  
  - API request building and response validation.  

- **Backend Handling**:
  - Graceful error handling (network errors, decoding failures).  
  - Data persistence with `UserDefaults` / `CoreData` (for caching).  
  - Retry logic and offline support.  

- **Architecture**:
  - **MVVM (Model-View-ViewModel)** for better testability.  
  - Dependency Injection for networking services.  
  - Scalable project structure.  

---

## 📱 Requirements
- iOS 15.0+  
- Xcode 14+  
- Swift 5+  

---

## 🧩 Installation
1. Clone the repository:
   ```bash
   [git clone https://github.com/yourusername/networking.git](https://github.com/Y-coderr/NetworkingTutorial.git)

