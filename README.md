# 🧠 AI Quiz Builder - QuizGenie

<img width="1536" height="1024" alt="AI_quiz_builder" src="https://github.com/user-attachments/assets/3e81efcf-d9d7-41ec-ae21-0b32eb6ccea9" />


**QuizGenie** is a smart quiz generation platform built with **Next.js 14 App Router**. It lets educators and content creators generate quizzes in real-time using AI, making interactive learning sessions seamless, fast, and dynamic.

This project was bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

---

## 🚀 Features

- 🔮 **AI-Powered Quiz Generation** - Enter a topic or paste content and get a quiz instantly
- 🧩 **Multiple Question Types** - MCQs, True/False, Fill-in-the-blanks and more
- ⚡ **Live Leaderboards** - Engage your audience with real-time competition(in progress...)
- 👥 **Multiplayer Support** - Participants can join from their devices and play simultaneously(in progress...)
- 📊 **Detailed Analytics** - Track performance per question and per user
- 🎨 **Retro Terminal UI** - Unique, nostalgic terminal-style design

---


## 🛠️ Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Backend**: Node.js (API routes in Next.js)
- **Authentication**: Context API (local auth)
- **AI Integration**: OpenAI API ( not included in this repo)
- **Deployment**: [Vercel](https://vercel.com)

---

## 🧰 Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/quizgenie.git
cd quizgenie


Install dependencies:

npm install
# or
yarn install



3000

🗂️ Project Structure (App Router)

app/
├── layout.tsx
├── page.tsx
├── login/
├── home/
├── quiz/
├── leaderboard/
components/
context/
lib/
public/
styles/

