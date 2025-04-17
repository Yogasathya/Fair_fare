# 🚖 Smart Ride Platform with Route-Based Advertising

This project is a PyQt5-based ride-booking application that aims to **reduce customer platform fees** by **monetizing advertisements from partner companies** placed along the route.

## 💡 Features

- 🔍 **Search for Drivers** based on pickup location from a CSV backend.
- ✅ **Confirm Rides** and get details like ETA, fare, driver info.
- 📱 **QR Code Generation** for ride confirmation.
- 💰 **Flexible Payment Options** (Cash, Card, UPI).
- 🗺️ **Real-time Map Integration** using Folium.
- 🛍️ **Route-based Shop Advertisements** from partnered companies like KFC, McDonald's, etc.
- 📉 **Reduces Platform Fees** for the customer by showing targeted ads en route.

## 🛠️ Tech Stack

- Python (PyQt5, Geopy, Folium, QWebEngineView)
- CSV-based driver backend
- QR Code generation (qrcode)
- GUI and Map integration

## 🗃️ File Structure

- `ride_app.py`: Main application logic
- `driver_details_with_location.csv`: Driver data with location info
- `ShopInfoWidget`: Popup offer display for shops
- `BrowserWindow`: Folium map with pickup, destination, and shop markers

## 🏁 How to Run

```bash
pip install pyqt5 folium geopy qrcode PyQtWebEngine
python ride_app.py
