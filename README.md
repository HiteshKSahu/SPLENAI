# SPLEN OS

### AI-Powered Personal Command Center

SPLEN OS is a web-based AI project planning dashboard designed to transform natural-language project ideas into structured, actionable development plans. It combines a futuristic interface with artificial intelligence to simplify project planning and improve developer productivity.

## 🚀 Features

- **AI-Powered Project Planning** — Generates project summaries, recommended technology stacks, estimated timelines, and development roadmaps.
- **Natural Language Command Interface** — Interact with AI using simple text commands.
- **Real-Time Dashboard** — Displays live time and date.
- **Activity Feed** — Displays generated AI responses dynamically.
- **Futuristic UI** — Features animated components, glowing elements, and a modern dark theme.
- **Productivity Dashboard** — Includes project, task, and note counter placeholders.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend development |
| Vite | Build and development tool |
| Tailwind CSS | UI styling |
| Framer Motion | Animations |
| Lucide React | Icons |
| Groq API | AI inference |
| Llama 3.3 70B | AI model |
| OpenAI SDK | API integration |

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/hiteshksahu13-cmd/SPLEN.git
cd SPLEN
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the root directory.

```env
VITE_GROQ_API_KEY=your_groq_api_key_here
```

Get your API key from https://console.groq.com/keys.

### 4. Run the application

```bash
npm run dev
```

Open the local URL displayed in the terminal, typically:

```text
http://localhost:5173
```

## 🧠 How It Works

1. The user enters a project idea into the command interface.
2. The application sends the input to the Groq API.
3. The Llama AI model processes the request.
4. The AI generates:
   - Project summary
   - Recommended technology stack
   - Estimated development time
   - Step-by-step development plan
5. The generated response appears in the Activity Feed.

## 💡 Example Command

```text
Build a student attendance management system
using React and Spring Boot.
```

SPLEN AI generates a structured development roadmap based on the given requirements.

## 📁 Project Structure

```text
SPLEN/
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## 📌 Current Status

SPLEN OS is currently a frontend prototype with AI integration. Dashboard counters are static, and generated responses are stored temporarily in React state.

The current implementation uses browser-side API requests. For production deployment, API credentials and requests should be moved to a secure backend.

## 🔮 Future Enhancements

- User authentication and authorization
- Database integration
- Real-time project and task management
- Personal notes management
- AI conversation history
- Personalized productivity workspace
- Secure backend API integration
- Exportable AI-generated project roadmaps

---

**SPLEN OS — Turning Ideas into Actionable Plans.**
