# 🎧 Moodify

**Moodify** is a simple, AI-assisted music recommendation web app built with the MERN stack. It helps users discover songs that match their mood — whether they’re feeling happy, sad, chill, or hype. With a minimal UI and smooth music player, Moodify takes the guesswork out of finding the perfect vibe.

## 🚀 Features

- 🎵 Mood-based music recommendations (happy, chill, sad, hype)
- 🧠 Optional AI integration for dynamic playlist generation
- 🎧 In-browser music player with play/pause/skip controls
- 😌 Simple mood selector interface
- 🖥️ Responsive UI built with TailwindCSS
- 🔐 (Optional) User authentication and saved mood history

## 🧠 How It Works

Users select their current mood, and Moodify responds with a curated list of songs that match that mood. Recommendations can be either hardcoded or powered by an AI API like OpenAI for more variety and creativity.

## 📦 Tech Stack

- **Frontend:** React.js, TailwindCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Optional AI:** OpenAI API (for smart playlist generation)

## 🛠️ Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/moodify.git
cd moodify

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

# Start backend
npm run dev

# Start frontend (in a new terminal)
cd ../client
npm start
