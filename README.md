# ManyChat Messenger & Telegram Delivery System

## 📌 Overview
This project is an automated message delivery system built using **ManyChat** integrated with **Facebook Messenger**, **Google Sheets**, and **Telegram**.  
It automates order processing and delivery notifications across platforms based on predefined chatbot flows.

## ⚙️ System Flow
1. Customer interacts with the Facebook Messenger chatbot to place an order.  
2. ManyChat processes the order details and stores them in Google Sheets.  
3. Google Sheets calculates the total amount and sends it back to ManyChat for payment confirmation.  
4. After payment is verified, ManyChat updates the order status in Google Sheets.  
5. Google Sheets assigns an available rider using a load-based assignment logic.  
6. Order and customer details are sent to the assigned rider via Telegram for pickup and delivery.  
7. The rider confirms completion by pressing the **“Order Delivered”** button in Telegram.  
8. Telegram sends the delivery status back to Google Sheets.  
9. Google Sheets updates ManyChat with the **Delivered** status.  
10. ManyChat notifies the customer that the order has been successfully delivered.

## 🧩 Platforms & Tools
- ManyChat  
- Facebook Messenger  
- Telegram Bot API
- Google Sheets  

## 🚀 Features
- Multi-channel message delivery  
- Automated chatbot flows  
- User-triggered actions  
- Centralized logic in ManyChat  

## 🛠️ Skills Demonstrated
- Chatbot flow design  
- Cross-platform automation  
- API integration  
- Conditional logic  

## 📸 Demo
Screenshots of the workflow and message delivery are included in this repository.
