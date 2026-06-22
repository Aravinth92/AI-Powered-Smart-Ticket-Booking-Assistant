<div align="center">

# 📚 BookAI
### AI-Powered Smart Ticket Booking Assistant

BookAI is an intelligent ticket booking application built with **React, TypeScript, Vite, and Google Gemini AI**. It understands natural language queries and provides ticket suggestions for flights, trains, movies, concerts, and events using AI-powered search and recommendations.

</div>

---

## ✨ Features

- 🤖 AI-powered conversational booking assistant
- ✈️ Flight ticket recommendations
- 🚆 Train ticket recommendations
- 🎬 Movie ticket suggestions
- 🎵 Concert and event booking assistance
- 🔍 Real-time web search integration using Gemini Search Tool
- 🎫 Beautiful downloadable ticket generation
- 💬 Natural language understanding
- 📱 Responsive and modern user interface
- ⚡ Fast and lightweight Vite application

---

## 🛠️ Tech Stack

### Frontend
- React 19
- TypeScript
- Vite
- Tailwind CSS
- Lucide React Icons
- Motion Animations

### AI & Backend Services
- Google Gemini API
- Google Search Tool Integration
- Express.js
- Dotenv

### Database
- Better SQLite3

---

## 📂 Project Structure

```text
BookAI/
│
├── src/
│   ├── services/
│   │   └── geminiService.ts
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── index.html
├── package.json
├── vite.config.ts
├── tsconfig.json
├── .env.example
└── README.md
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/bookai.git
cd bookai
```

### Install Dependencies

```bash
npm install
```

---

## 🔑 Environment Variables

Create a `.env.local` file:

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

Get your Gemini API Key from:

https://aistudio.google.com/

---

## ▶️ Run Development Server

```bash
npm run dev
```

Application will run at:

```text
http://localhost:3000
```

---

## 🏗️ Build for Production

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

## 💡 Example Queries

### Flight Booking
```text
Book a flight from Chennai to Delhi tomorrow for 2 passengers.
```

### Train Booking
```text
Find trains from Bangalore to Hyderabad on Friday.
```

### Movie Booking
```text
Book movie tickets for Kalki tonight.
```

### Concert Booking
```text
Find concert tickets in Chennai this weekend.
```

---

## 🧠 How It Works

1. User enters a booking request in natural language.
2. Gemini AI extracts:
   - Booking type
   - Source and destination
   - Date and time
   - Number of passengers
3. Google Search Tool retrieves available options.
4. AI returns structured ticket recommendations.
5. User can view and download generated tickets.

---

## 📸 Features Showcase

- AI Chat Interface
- Ticket Recommendation Cards
- Downloadable Tickets
- Responsive Design
- Real-Time Search Integration

---

## 📦 Dependencies

```text
React
TypeScript
Vite
Google Gemini AI SDK
Tailwind CSS
Express.js
Better SQLite3
Lucide React
Motion
Dotenv
```

---

## 🔮 Future Enhancements

- Payment Gateway Integration
- User Authentication
- Booking History
- Email Ticket Delivery
- Seat Selection
- Hotel Recommendations
- Multi-language Support
- Voice-based Booking Assistant

---

## 👨‍💻 Author

**Aravinth Periyasamy**

M.Sc Data Science | AI & ML Engineer | AWS Cloud Enthusiast

Skills:
- Machine Learning
- Generative AI
- Agentic AI
- AWS Cloud Computing
- Data Analytics
- Full Stack Development

---

## 📄 License

This project is licensed under the MIT License.

---

<div align="center">

⭐ If you like this project, give it a star on GitHub!

Made with ❤️ using React, TypeScript and Google Gemini AI

</div>
