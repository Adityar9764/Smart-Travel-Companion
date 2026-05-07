# AI-Powered Smart Travel Companion 🌍✈️

An AI-driven travel planning and booking platform built using the MERN stack. The application helps users discover destinations, generate personalized travel itineraries, receive smart recommendations based on preferences, and securely book trips using Razorpay UPI integration.

---

# 🚀 Features

## 🤖 AI Travel Planner
Generate personalized travel itineraries using AI based on:
- Budget
- Destination
- Trip duration
- Interests
- Travel style

### Example Prompt
> “Plan a 5-day Goa trip under ₹25,000 with beaches and nightlife.”

### AI Generates
- Day-wise itinerary
- Recommended attractions
- Food suggestions
- Budget breakdown
- Travel tips

---

## 🎯 Smart Destination Recommendations
Personalized destination suggestions based on:
- User interests
- Search history
- Budget preferences
- Seasonal trends

### Recommendation Examples
- Adventure → Manali, Rishikesh
- Beaches → Goa, Bali
- Luxury → Dubai, Maldives

---

## 💳 Razorpay UPI Payments
Secure online payment integration using Razorpay:
- UPI payments
- Booking checkout
- Payment verification
- Order management

---

## 🔐 Authentication & Authorization
- JWT-based authentication
- Secure login/signup
- Protected routes
- User session handling

---

## 📱 Responsive UI
- Mobile-friendly interface
- Modern React-based UI
- Fast and interactive experience

---

# 🛠️ Tech Stack

## Frontend
- React.js
- React Router
- Axios
- Tailwind CSS / CSS

---

## Backend
- Node.js
- Express.js

---

## Database
- MongoDB
- Mongoose

---

## AI Integration
- OpenAI API / Gemini API
- Embedding-based recommendation system
- Cosine similarity matching

---

## Payment Gateway
- Razorpay UPI Integration

---

## Authentication
- JWT (JSON Web Tokens)
- bcrypt.js

---

# 🧠 AI Features

## 1. AI Itinerary Generation
Uses Large Language Models (LLMs) to generate:
- Dynamic travel plans
- Personalized schedules
- Budget-aware recommendations

---

## 2. Recommendation Engine
A lightweight recommendation system using:
- User preference embeddings
- Destination tagging
- Similarity matching

---

# 📂 Project Structure

```bash
AI-Travel-Companion/
│
├── client/                 # React Frontend
│   ├── public/
│   ├── src/
│   └── package.json
│
├── server/                 # Node.js Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── services/
│   └── package.json
│
├── .env
├── README.md
└── package.json
```

---

# ⚙️ Installation & Setup

## 1. Clone Repository

```bash
git clone https://github.com/your-username/AI-Travel-Companion.git

cd AI-Travel-Companion
```

---

## 2. Install Dependencies

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd ../server
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

OPENAI_API_KEY=your_openai_api_key

RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_secret
```

---

# ▶️ Running the Application

## Start Backend

```bash
cd server
npm run dev
```

---

## Start Frontend

```bash
cd client
npm start
```

---

# 🌐 API Overview

## Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register user |
| POST | `/api/auth/login` | Login user |

---

## AI Planner

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/ai/generate-trip` | Generate itinerary |

---

## Recommendations

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/destinations/recommend` | Personalized destinations |

---

## Payments

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/payment/create-order` | Create Razorpay order |
| POST | `/api/payment/verify` | Verify payment |

---

# 🔒 Security Features

- Password hashing using bcrypt
- JWT authentication
- Protected API routes
- Environment variable protection
- Secure payment verification

---

# 📈 Future Enhancements

- Real-time weather integration
- Flight & hotel APIs
- AI chatbot assistant
- Voice-based trip planning
- Saved itineraries
- Social trip sharing
- Multi-language support

---

# 🧪 Sample AI Prompt

```text
Plan a 4-day budget-friendly Goa trip for friends with nightlife, beaches, and local food recommendations under ₹20,000.
```

---

# 📸 Screenshots

Add application screenshots here.

### Suggested Screenshots
- Homepage
- AI Planner
- Destination Recommendations
- Razorpay Payment Page
- User Dashboard

---

# 🚀 Deployment

## Frontend
- Vercel
- Netlify

## Backend
- Render
- Railway

## Database
- MongoDB Atlas

---

# 🤝 Contributing

Contributions are welcome.

### Steps
1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed by **Your Name**

GitHub: https://github.com/your-username

---

# ⭐ Support

If you found this project useful:
- Star the repository
- Fork the project
- Share feedback

---

# 📌 Project Summary

AI-Powered Smart Travel Companion combines:
- Artificial Intelligence
- Personalized recommendations
- Secure online booking
- Modern MERN architecture

to deliver a smarter and more personalized travel planning experience.
