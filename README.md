# AuctionPlanet 🎯

AuctionPlanet is a full-featured online auction web application built with **ASP.NET MVC 5**, following a clean **three-tier architecture**. It allows users to list items, bid in real time, and manage auctions with role-based access.

## 🔧 Technologies Used

- **Backend**: C#, ASP.NET MVC 5, Entity Framework
- **Frontend**: Razor Views, HTML5, CSS3, Bootstrap
- **Database**: SQL Server
- **Architecture**: MVC + Services + Repositories (3-Layered Architecture)

## ✨ Features

- ✅ User registration & login
- 🛍️ List items for auction
- 💰 Real-time bidding logic
- ⏳ Auction timers (start/end logic)
- 📜 Bid history tracking
- 🔒 Role-based access (admin/user)

## 🏗️ Project Structure

/Controllers → Handle routing & UI logic
/Models → Domain models (User, Item, Bid)
/Views → Razor pages
/Services → Business logic (auction rules)
/Repositories → DB access using Entity Framework


## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/sandeepsandy619/Auction.git
   cd Auction
2.Open in Visual Studio

3.Set up your SQL Server connection string in Web.config

4.Run the project (F5) — browse to localhost:xxxx
