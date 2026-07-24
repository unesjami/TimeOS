# ⏳ TimeOS · Smart Planner

An AI-powered, zero-based time planning repository that brings intentional, automated scheduling to your daily routine. **TimeOS** transforms how teams and individuals manage their days by seamlessly turning calendar events, natural language inputs, and meeting context into action items.

---

## 🚀 Key Features

* **Zero-Based Time Planning:** Assign a specific purpose to every single hour of your day.
* **AI Smart Auto-Scheduling:** Dynamically fits tasks around your real-time schedule and deadlines.
* **Autonomous Meeting Assistant:** Automatically records, transcribes, and structures notes across Zoom, Teams, and Google Meet.
* **Follow-up Agent:** Autogenerates polished summary emails and lists directly from your conversations.
* **Two-Way Calendar Sync:** Instantly mirrors plans across Google Calendar, Apple Calendar, and Outlook.
* **Full Offline Support:** Rest assured your data remains secure and editable completely on-device without an active internet connection.

---

## 🛠️ Tech Stack

* **Frontend:** React.js / Next.js, Tailwind CSS, TypeScript
* **Backend:** Node.js, Express
* **AI Layer:** OpenAI GPT APIs / LangChain
* **Database & Auth:** PostgreSQL / Prisma, NextAuth.js
* **Integrations:** Google Calendar API, Zoom SDK, Microsoft Graph API

---

## 💻 Getting Started

Follow these steps to set up the repository locally.

### Prerequisites

Ensure you have the following installed:
* [Node.js](https://nodejs.org) (v18 or higher)
* [npm](https://npmjs.com) or [yarn](https://yarnpkg.com)
* A PostgreSQL instance

### Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd timeos-smart-planner
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   Create a `.env` file in the root directory and add your credentials:
   ```env
   DATABASE_URL="postgresql://user:password@localhost:5432/timeos"
   OPENAI_API_KEY="your-openai-api-key"
   GOOGLE_CLIENT_ID="your-google-client-id"
   GOOGLE_CLIENT_SECRET="your-google-client-secret"
   NEXTAUTH_SECRET="your-nextauth-secret"
   ```

4. **Run database migrations:**
   ```bash
   npx prisma migrate dev
   ```

5. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open `http://localhost:3000` in your browser to view the application.

---

## 🧪 Running Tests

To execute the test suite, run the following command:
```bash
npm run test
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these quick steps:
1. **Fork** the project repository.
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`).
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`).
4. **Push** to the branch (`git push origin feature/AmazingFeature`).
5. **Open** a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
