AI-Powered Smart Travel Companion 🌍✈️

An AI-driven travel planning and booking platform built using the MERN stack.
The application helps users discover destinations, generate personalized travel itineraries, receive smart recommendations based on preferences, and securely book trips using Razorpay UPI integration.

🚀 Features
🤖 AI Travel Planner

Generate personalized travel itineraries using AI based on:

Budget
Destination
Trip duration
Interests
Travel style

Example:

“Plan a 5-day Goa trip under ₹25,000 with beaches and nightlife.”

The AI generates:

Day-wise itinerary
Recommended attractions
Food suggestions
Budget breakdown
Travel tips
🎯 Smart Destination Recommendations

Personalized destination suggestions based on:

User interests
Search history
Budget preferences
Seasonal trends

Recommendation examples:

Adventure → Manali, Rishikesh
Beaches → Goa, Bali
Luxury → Dubai, Maldives
💳 Razorpay UPI Payments

Secure online payment integration using Razorpay:

UPI payments
Booking checkout
Payment verification
Order management
🔐 Authentication & Authorization
JWT-based authentication
Secure login/signup
Protected routes
User session handling
📱 Responsive UI
Mobile-friendly interface
Modern React-based UI
Fast and interactive experience
🛠️ Tech Stack
Frontend
React.js
React Router
Axios
CSS / Tailwind CSS (optional)
Backend
Node.js
Express.js
Database
MongoDB
Mongoose ODM
AI Integration
OpenAI API / Gemini API
Embedding-based recommendation system
Cosine similarity matching
Payment Gateway
Razorpay UPI Integration
Authentication
JWT (JSON Web Tokens)
bcrypt.js
🧠 AI Features
1. AI Itinerary Generation

Uses Large Language Models (LLMs) to generate:

Dynamic travel plans
Personalized schedules
Budget-aware recommendations
2. Recommendation Engine

A lightweight recommendation system using:

User preference embeddings
Destination tagging
Similarity matching
📂 Project Structure
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
⚙️ Installation & Setup
1. Clone Repository
git clone <your-repository-url>
cd AI-Travel-Companion
2. Install Dependencies
Frontend
cd client
npm install
Backend
cd ../server
npm install
🔑 Environment Variables

Create a .env file inside the server directory.

PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

OPENAI_API_KEY=your_openai_api_key

RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_secret
▶️ Running the Application
Start Backend
cd server
npm run dev
Start Frontend
cd client
npm start
🌐 API Overview
Authentication
Method	Endpoint	Description
POST	/api/auth/register	Register user
POST	/api/auth/login	Login user
AI Planner
Method	Endpoint	Description
POST	/api/ai/generate-trip	Generate itinerary
Recommendations
Method	Endpoint	Description
GET	/api/destinations/recommend	Personalized destinations
Payments
Method	Endpoint	Description
POST	/api/payment/create-order	Create Razorpay order
POST	/api/payment/verify	Verify payment
🔒 Security Features
Password hashing using bcrypt
JWT authentication
Protected API routes
Environment variable protection
Secure payment verification
📈 Future Enhancements
Real-time weather integration
Flight & hotel APIs
AI chatbot assistant
Voice-based trip planning
Saved itineraries
Social trip sharing
Multi-language support
🧪 Sample AI Prompt
Plan a 4-day budget-friendly Goa trip for friends with nightlife, beaches, and local food recommendations under ₹20,000.
📸 Screenshots

Add application screenshots here.

Example:

Homepage
AI Planner
Recommendations
Payment Checkout
🚀 Deployment
Frontend
Vercel
Netlify
Backend
Render
Railway
Database
MongoDB Atlas
🤝 Contributing

Contributions are welcome.

Steps:

Fork the repository
Create a feature branch
Commit changes
Push to your branch
Open a Pull Request
📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Developed by [Your Name]

GitHub: https://github.com/your-username

⭐ Support

If you found this project useful:

Star the repository
Fork the project
Share feedback
📌 Project Summary

AI-Powered Smart Travel Companion combines:

Artificial Intelligence
Personalized recommendations
Secure online booking
Modern MERN architecture

to deliver a smarter and more personalized travel planning experience.
