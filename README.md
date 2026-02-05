# 💎 RV Jewellery - Complete E-commerce Solution

## 🕉️ ॐ श्री गणेशाय नमः 🕉️

A full-stack jewellery management and e-commerce platform with inventory management, billing system, and UPI payment integration.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen)
![MongoDB](https://img.shields.io/badge/database-MongoDB-green)
![Status](https://img.shields.io/badge/status-active-success)

---

## 🌟 Features

### 👨‍💼 Admin Features
- ✅ Product management with image upload
- ✅ Inventory tracking (stock status)
- ✅ Invoice generation with optional GST
- ✅ Customer management
- ✅ Sales reports and analytics
- ✅ Multiple authentication methods

### 👥 Customer Features
- ✅ Browse product catalog
- ✅ View product images and details
- ✅ Filter by category
- ✅ Search functionality
- ✅ Contact for purchase

### 🔐 Authentication
- ✅ Email/Password login
- ✅ Google OAuth 2.0
- ✅ Facebook OAuth
- ✅ Phone OTP (MSG91)
- ✅ Role-based access (Admin/Customer)

### 💳 Payment Integration
- ✅ UPI payment support
- ✅ Razorpay integration
- ✅ Invoice download/print

---

## 🛠️ Tech Stack

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### Services
- Firebase (Authentication & Storage)
- MongoDB Atlas (Database)
- Razorpay (Payments)
- MSG91 (SMS/OTP)

---

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- MongoDB Atlas account
- Firebase account
- Razorpay account (for payments)

### 1. Clone Repository

```bash
git clone https://github.com/YOUR-USERNAME/rv-jewellery.git
cd rv-jewellery
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create `.env` file in `backend/` folder:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
MSG91_AUTH_KEY=your_msg91_auth_key
MSG91_SENDER_ID=your_sender_id
```

Start backend:
```bash
npm start
```

Backend runs on: `http://localhost:5000`

### 3. Frontend Setup

```bash
cd frontend
npx http-server -p 8000
```

Frontend runs on: `http://localhost:8000`

### 4. Run Both Together

From project root:
```bash
# Linux/Mac
./run-fullstack.sh

# Windows
run-fullstack.bat
```

---

## 🚀 Deployment

### Backend Deployment (Render.com - FREE)

1. Push code to GitHub
2. Go to [Render.com](https://render.com)
3. Create new Web Service
4. Connect GitHub repository
5. Build command: `cd backend && npm install`
6. Start command: `cd backend && npm start`
7. Add environment variables from `.env`
8. Deploy!

### Frontend Deployment (Vercel - FREE)

1. Go to [Vercel](https://vercel.com)
2. Import GitHub repository
3. Root directory: `frontend`
4. Deploy!

**Update API URL in frontend after backend deployment**

---

## 📸 Screenshots

### Login Page
Beautiful authentication with Google, Facebook, and Phone OTP

### Admin Dashboard
Complete inventory management with image upload

### Product Catalog
Customer-facing product showcase

*(Add screenshots to /screenshots folder)*

---

## 🔒 Security Features

- ✅ Environment variables for sensitive data
- ✅ JWT token authentication
- ✅ Password hashing (bcrypt)
- ✅ CORS protection
- ✅ Input validation
- ✅ Session management
- ✅ .gitignore for sensitive files

---

## 📝 API Documentation

### Authentication Endpoints

```
GET  /auth/google          - Initiate Google OAuth
GET  /auth/google/callback - Google OAuth callback
GET  /auth/logout          - Logout user
GET  /auth/user            - Get current user
```

### Product Endpoints

```
GET    /api/products       - Get all products
POST   /api/products       - Create product (Admin only)
PUT    /api/products/:id   - Update product (Admin only)
DELETE /api/products/:id   - Delete product (Admin only)
```

### Invoice Endpoints

```
GET    /api/invoices       - Get all invoices (Admin only)
POST   /api/invoices       - Create invoice (Admin only)
GET    /api/invoices/:id   - Get invoice by ID
```

### Payment Endpoints

```
POST   /api/payment/create-order  - Create Razorpay order
POST   /api/payment/verify        - Verify payment
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**RV Jewellery Team**
- Location: Suraj Nagar
- Email: rvjewellery@example.com
- Website: [Coming Soon]

---

## 🙏 Acknowledgments

- MongoDB Atlas for database hosting
- Firebase for authentication
- Razorpay for payment gateway
- Render.com for backend hosting
- Vercel for frontend hosting
- All open-source contributors

---

## 📞 Support

For support:
- Email: rvjewellery@example.com
- Create an issue in this repository
- Contact: Suraj Nagar

---

## 🕉️ Blessing

**ॐ श्री गणेशाय नमः**

May Lord Ganesha bless this project and remove all obstacles from the path of development and business success!

---

## 📊 Project Status

🟢 **Active Development**

Current Version: 1.0.0

Last Updated: February 2026

---

## 🗺️ Roadmap

- [x] Basic authentication system
- [x] Product management with images
- [x] Invoice generation with GST
- [x] Payment integration (Razorpay/UPI)
- [x] Admin and customer dashboards
- [ ] Email notifications
- [ ] WhatsApp integration for orders
- [ ] Mobile app (React Native)
- [ ] Multi-language support
- [ ] Advanced analytics dashboard
- [ ] Inventory auto-alerts
- [ ] Customer loyalty program

---

## 📈 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/YOUR-USERNAME/rv-jewellery)
![GitHub contributors](https://img.shields.io/github/contributors/YOUR-USERNAME/rv-jewellery)
![GitHub stars](https://img.shields.io/github/stars/YOUR-USERNAME/rv-jewellery?style=social)
![GitHub forks](https://img.shields.io/github/forks/YOUR-USERNAME/rv-jewellery?style=social)

---

**Made with ❤️ by RV Jewellery Team**

**🕉️ ॐ श्री गणेशाय नमः 🕉️**

---

**⭐ Star this repo if you find it helpful!**
