# QuickStay - FullStack Hotel Booking Application

QuickStay is a modern, full-stack hotel booking application that allows users to search, book, and manage hotel reservations. The application features a robust backend API with user authentication and hotel management capabilities.

## 🚀 Features

### Backend Features
- **User Authentication & Authorization** - Role-based access control (users, hotel owners, admin)
- **Hotel Management** - Hotel owners can register and manage their properties
- **Booking System** - Users can search and book hotels
- **RESTful API** - Clean and well-structured API endpoints
- **MongoDB Integration** - NoSQL database for flexible data storage

### Frontend Features 
- **Responsive Design** - Mobile-first responsive design
- **Hotel Search & Filtering** - Advanced search with filters
- **Booking Management** - User dashboard for managing bookings
- **Payment Integration** - Secure payment processing
- **Reviews & Ratings** - User reviews and rating system

## 🛠️ Tech Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - ODM for MongoDB
- **JWT** - Authentication tokens
- **bcrypt** - Password hashing

### Frontend (Planned)
- **React.js** - Frontend framework
- **Redux** - State management
- **Tailwind CSS** - Styling framework
- **Axios** - HTTP client

## 📁 Project Structure

```
QuickStay-FullStack/
├── server/
│   ├── controllers/          # Route controllers
│   ├── models/              # Database models
│   ├── routes/              # API routes
│   ├── middleware/          # Custom middleware
│   ├── config/              # Configuration files
│   └── server.js           # Server entry point
├── client/                  # Frontend application
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   └── utils/
│   └── public/
├── .env                     # Environment variables
└── package.json             # Dependencies
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/dhaval4133/Hotel-Booking.git
   ```

2. **Install backend dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the server directory:
   ```env
   MONGODB_URI=------- MONGODB_URI -------

   CLOUDINARY_CLOUD_NAME=-------CLOUDINARY_CLOUD_NAME  -------
   CLOUDINARY_API_KEY=------- CLOUDINARY_API_KEY -------
   CLOUDINARY_API_SECRET=------- CLOUDINARY_API_SECRET -------
   
   CLERK_PUBLISHABLE_KEY=------ CLERK_PUBLISHABLE_KE -------
   CLERK_SECRET_KEY=------- CLERK_SECRET_KEYt -------
   CLERK_WEBHOOK_SECRET=------- CLERK_WEBHOOK_SECRET -------

   STRIPE_PUBLISHABLE_KEY=------- STRIPE_PUBLISHABLE_KEY -------
   STRIPE_SECRET_KEY=------- STRIPE_SECRET_KEY= -------
   STRIPE_WEBHOOK_SECRET=------- STRIPE_WEBHOOK_SECRET -------

   SENDER_EMAIL=------- SENDER_EMAIL -------
   SMTP_USER=------- SMTP_USER -------
   SMTP_PASS=------- SMTP_PASS -------
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Set up frontend (when implemented)**
   ```bash
   cd ../client
   npm install
   npm start
   ```

## 🧪 Testing

Run tests with:
```bash
npm test
```

## 📦 Deployment

### Backend Deployment
1. Set production environment variables
2. Build the application
3. Deploy to your preferred platform (Heroku, AWS, DigitalOcean)

### Frontend Deployment
1. Build the React app
2. Deploy to Netlify, Vercel, or similar platforms

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name - [@Dhaval Dangar](https://github.com/dhaval4133)

## 🙏 Acknowledgments

- Inspired by modern hotel booking platforms
- Built with love for the travel and hospitality industry

⭐ Star this repo if you found it helpful!
