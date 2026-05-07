# 🎧 Psychic Chat & Call Platform

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-22-339933?logo=nodedotjs)](https://nodejs.org/)
[![Socket.io](https://img.shields.io/badge/Socket.io-RealTime-010101?logo=socketdotio)](https://socket.io/)
[![Twilio](https://img.shields.io/badge/Twilio-Voice-F22F46?logo=twilio)](https://twilio.com)
[![Stripe](https://img.shields.io/badge/Stripe-Payments-008CDD?logo=stripe)](https://stripe.com)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb)](https://mongodb.com)
[![JWT](https://img.shields.io/badge/JWT-Auth-000000?logo=jsonwebtokens)](https://jwt.io)

## 📌 Overview

A complete platform connecting users with psychics for chat and audio/video calls. Includes real-time messaging, call system, credit-based payments, and revenue sharing (75% psychic / 25% platform).

> ⭐ **Star this repository** if you find it useful!

---

## ✨ Key Features

### 👤 User Features
| Feature | Description |
|---------|-------------|
| Register/Login | JWT authentication |
| Credit Purchase | Stripe integration |
| Browse Psychics | Filter by category, rating, price |
| Real-time Chat | Socket.io messaging |
| Audio/Video Calls | Twilio integration |
| Rate & Review | Rate psychics after session |
| History | View call/chat history |
| Free Credits | 5 free credits on signup |

### 🔮 Psychic Features
| Feature | Description |
|---------|-------------|
| Professional Profile | Setup with hourly rates |
| Availability | Manage online/offline status |
| Real-time Chat | Instant messaging with users |
| Call Management | Accept/reject calls |
| Earnings Dashboard | View earnings |
| Withdrawals | 75% platform / 25% psychic |

### 👨‍💼 Admin Features
| Feature | Description |
|---------|-------------|
| Psychic Approval | Approve/reject applications |
| User Management | View, edit, block users |
| Psychic Management | Manage psychic profiles |
| Commission Settings | Set platform commission (75/25) |
| Transaction View | View all transactions |
| Security System | Auto-block on violations |

### 🔒 Security Features
- Automated link detection in chat
- 3-strike system (email/phone/website sharing)
- Auto-block after 3 violations
- Chat monitoring
- Spam protection

### 💰 Payment System
| Feature | Description |
|---------|-------------|
| Stripe Integration | Credit card payments |
| Credit System | Buy credits for calls/chats |
| Revenue Split | 75% psychic / 25% platform |
| Free Credits | 5 credits on new account |
| Transaction History | Complete history |

### 📡 Real-time Features
| Feature | Technology |
|---------|------------|
| Instant Messaging | Socket.io |
| Voice Calls | Twilio Voice API |
| Video Calls | Twilio Video API |
| Online Status | Real-time presence |
| Typing Indicators | Socket.io |
| Read Receipts | Socket.io |

---

## 🛠️ Technical Architecture

### Frontend
