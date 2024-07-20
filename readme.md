# E-Commerce Project

**Student Name**: Nidhi Thakkar  
**Student Number**: 8982055 
**Date**: 2024-07-19

### Technology Stack

**Frontend**: ReactJS  
**Backend**: Node.js with Express  
**Database**: MongoDB (Atlas)

### Project Setup

1. **Project Initialization**: Repository created on GitHub.
2. **Frontend Setup**: Initialized ReactJS project.
3. **Backend Setup**: Initialized Node.js 

### Database Schema Design

**Products Schema (MongoDB)**

- `product_id`: number
- `name`: String
- `description`: String
- `price`: Number
- `category`: String
- `stock`: Number
- `imageUrl`: String

**Users Schema (MongoDB)**

- `user_id`: number
- `username`: String
- `password`: String
- `email`: String
- `phone`: number
- `address`: String

**Orders Schema (MongoDB)**

- `order_id`: String
- `user_id`: String
- `date`: String
- `amount`: number
- `payment_type`: String