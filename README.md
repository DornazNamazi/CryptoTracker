# 🚀 CryptoTracker — iOS App (SwiftUI)

CryptoTracker is a modern iOS application built with **SwiftUI**, **MVVM architecture**, **Core Data**, and live cryptocurrency market data using the **CoinGecko API**.  
It provides real-time prices, market statistics, search, portfolio tracking, and a clean UI optimized for both light and dark mode.

---

## 🌟 Features

### 📊 Real-Time Market Data
- Live cryptocurrency prices from **CoinGecko API**
- Market cap, volume, price change %
- Beautiful chart views
- Pull-to-refresh

### 🔎 Smart Search Bar
- Search any crypto instantly
- Auto-updating results
- Smooth animations + SwiftUI transitions

### 💼 Portfolio Tracking
- Add coins with your purchase price
- See total portfolio value
- Track profit/loss
- Stored locally using **Core Data**

### 🎨 Clean SwiftUI Interface
- Custom components
- Dark/Light mode support
- Smooth animations
- Reusable views & extensions

---

## 🛠️ Technologies Used

- **Swift 5**
- **SwiftUI**
- **Combine**
- **MVVM Architecture**
- **Core Data (Portfolio Storage)**
- **CoinGecko API**
- **URLSession + Decodable**
- **AsyncImage / Caching**
- **Charts / Animations**

---

## 📁 Project Structure

CryptoTracker/
│
├── Models/
│ ├── Coin.swift
│ ├── MarketData.swift
│ └── PortfolioEntity (Core Data)
│
├── ViewModels/
│ ├── HomeViewModel.swift
│ ├── PortfolioViewModel.swift
│ └── CoinDetailViewModel.swift
│
├── Views/
│ ├── HomeView.swift
│ ├── CoinRowView.swift
│ ├── CoinDetailView.swift
│ ├── SearchBarView.swift
│ ├── PortfolioView.swift
│ └── StatisticsView.swift
│
├── Services/
│ ├── NetworkManager.swift
│ ├── CoinGeckoAPI.swift
│ └── DataService.swift
│
└── Utilities/
├── Extensions/
└── Helpers/



---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/CryptoTracker.git
   
    Open the project

    Open CryptoTracker.xcodeproj using Xcode

    No API key required!

    CoinGecko API is free and keyless

    App will fetch data instantly

    Run the app

    Command + R
