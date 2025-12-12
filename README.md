<div align="center">

# 🤖 ChatBot AI App

### The Ultimate Open-Source AI Chat Interface for Everyone

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/apollodev1107-star/ChatBot-AI-App)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Next.js](https://img.shields.io/badge/Next.js-14.1-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-18.0-61dafb)](https://reactjs.org/)
[![Supabase](https://img.shields.io/badge/Supabase-2.38-green)](https://supabase.com/)
[![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

[🚀 Live Demo](#) • [📖 Documentation](#documentation) • [💬 Discussions](https://github.com/apollodev1107-star/ChatBot-AI-App/discussions) • [🐛 Report Bug](https://github.com/apollodev1107-star/ChatBot-AI-App/issues)

---

<img src="./public/readme/screenshot.png" alt="Chatbot UI Dashboard" width="800" style="border-radius: 10px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">

</div>

---

## 📊 Project Statistics

<div align="center">

| Metric | Value |
|--------|-------|
| **Total Commits** | 264+ |
| **Project Start** | January 2018 |
| **Latest Update** | December 2025 |
| **Tech Stack** | Next.js, React, TypeScript, Supabase |
| **AI Providers** | OpenAI, Anthropic, Google, Azure, Mistral |
| **Languages** | TypeScript, JavaScript, SQL |

</div>

---

## ✨ Key Features

<div align="center">

### 🎯 Core Capabilities

| Feature | Description |
|---------|-------------|
| 🤖 **Multi-AI Support** | Integrate with OpenAI, Anthropic Claude, Google Gemini, Azure OpenAI, and Mistral |
| 💬 **Advanced Chat Interface** | Beautiful, responsive chat UI with markdown support, code highlighting, and file attachments |
| 🔒 **Secure Authentication** | Built-in user authentication with Supabase |
| 📁 **File Management** | Upload and process PDFs, documents, and images |
| 🌐 **Multi-language** | Internationalization support (i18n) |
| 🎨 **Dark Mode** | Beautiful dark and light themes |
| 📱 **Mobile Responsive** | Fully optimized for mobile devices |
| 🔍 **RAG Support** | Retrieval-Augmented Generation with vector embeddings |
| 🛠️ **Custom Assistants** | Create and manage custom AI assistants |
| 📊 **Workspace Management** | Organize chats and data in workspaces |

</div>

---

## 🛠️ Tech Stack

<div align="center">

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-14.1-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-18.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend & Database
![Supabase](https://img.shields.io/badge/Supabase-2.38-3ECF8E?style=for-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### AI & ML
![OpenAI](https://img.shields.io/badge/OpenAI-4.23-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-Claude-FF6B35?style=for-the-badge)
![Google AI](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

### Tools & Libraries
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-20.10-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-29.7-C21325?style=for-the-badge&logo=jest&logoColor=white)

</div>

---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- Docker (for local Supabase)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/apollodev1107-star/ChatBot-AI-App.git
cd ChatBot-AI-App

# Install dependencies
npm install

# Start Supabase locally
supabase start

# Copy environment variables
cp .env.local.example .env.local

# Run the development server
npm run chat
```

Visit [http://localhost:3000](http://localhost:3000) to see your app!

---

## 📁 Project Structure

```
ChatBot-AI-App/
├── app/                    # Next.js app directory
│   ├── api/               # API routes
│   ├── [locale]/          # Internationalized routes
│   └── auth/              # Authentication
├── components/            # React components
│   ├── chat/              # Chat-related components
│   ├── messages/          # Message components
│   ├── sidebar/           # Sidebar components
│   └── ui/                # UI primitives
├── db/                    # Database schemas
├── lib/                   # Utility libraries
├── public/                # Static assets
├── supabase/              # Supabase configuration
│   └── migrations/        # Database migrations
└── types/                 # TypeScript types
```

---

## 🎨 Features Showcase

### 🤖 Multi-AI Provider Support
Connect to multiple AI providers simultaneously:
- **OpenAI** (GPT-4, GPT-3.5)
- **Anthropic** (Claude 3)
- **Google** (Gemini Pro)
- **Azure OpenAI**
- **Mistral AI**

### 💬 Advanced Chat Features
- Real-time streaming responses
- Markdown rendering with syntax highlighting
- Code block execution
- File attachments (PDF, images, documents)
- Message editing and deletion
- Conversation history

### 🔒 Security & Privacy
- Secure authentication with Supabase
- Encrypted data storage
- Role-based access control
- Workspace isolation

### 📊 Analytics & Monitoring
- Built-in analytics dashboard
- Usage tracking
- Performance monitoring
- Error logging

---

## 🧪 Testing

```bash
# Run unit tests
npm test

# Run E2E tests
cd __tests__/playwright-test
npm test
```

---

## 📈 Performance

- ⚡ **Fast Initial Load**: Optimized bundle size with code splitting
- 🚀 **Server-Side Rendering**: Next.js SSR for better SEO
- 💾 **Efficient Caching**: Smart caching strategies
- 📱 **Mobile Optimized**: Responsive design for all devices

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- UI components from [Radix UI](https://www.radix-ui.com/)
- Icons from [Tabler Icons](https://tabler.io/icons)
- Database powered by [Supabase](https://supabase.com/)

---

## 📞 Contact & Support

- **GitHub Issues**: [Report a bug](https://github.com/apollodev1107-star/ChatBot-AI-App/issues)
- **Discussions**: [Join the discussion](https://github.com/apollodev1107-star/ChatBot-AI-App/discussions)
- **Email**: [Your Email]

---

<div align="center">

### ⭐ Star this repo if you find it helpful!

**Made with ❤️ by [apollodev1107-star](https://github.com/apollodev1107-star)**

[![GitHub stars](https://img.shields.io/github/stars/apollodev1107-star/ChatBot-AI-App.svg?style=social&label=Star)](https://github.com/apollodev1107-star/ChatBot-AI-App)
[![GitHub forks](https://img.shields.io/github/forks/apollodev1107-star/ChatBot-AI-App.svg?style=social&label=Fork)](https://github.com/apollodev1107-star/ChatBot-AI-App)

</div>

---

## 📚 Documentation

### Local Development

<details>
<summary>Click to expand setup instructions</summary>

#### 1. Clone the Repo

```bash
git clone https://github.com/apollodev1107-star/ChatBot-AI-App.git
cd ChatBot-AI-App
```

#### 2. Install Dependencies

```bash
npm install
```

#### 3. Install Supabase & Run Locally

**Why Supabase?**

We use Supabase because it's:
- Easy to use
- Open-source
- Built on PostgreSQL
- Has a free tier for hosted instances

**Installation Steps:**

1. **Install Docker** - Download from [here](https://docs.docker.com/get-docker)

2. **Install Supabase CLI**

   **MacOS/Linux:**
   ```bash
   brew install supabase/tap/supabase
   ```

   **Windows:**
   ```bash
   scoop bucket add supabase https://github.com/supabase/scoop-bucket.git
   scoop install supabase
   ```

3. **Start Supabase**
   ```bash
   supabase start
   ```

#### 4. Fill in Secrets

1. **Environment Variables**
   ```bash
   cp .env.local.example .env.local
   ```

   Get the required values by running:
   ```bash
   supabase status
   ```

   Fill in your `.env.local` file with the values from `supabase status`.

2. **SQL Setup**

   In the 1st migration file `supabase/migrations/20240108234540_setup.sql`, replace:
   - `project_url` (line 53)
   - `service_role_key` (line 54)

#### 5. Install Ollama (Optional)

For local models, follow instructions [here](https://github.com/jmorganca/ollama#macos).

#### 6. Run App Locally

```bash
npm run chat
```

Your app will be running at [http://localhost:3000](http://localhost:3000)

</details>

### Hosted Deployment

<details>
<summary>Click to expand deployment instructions</summary>

#### Setup Backend with Supabase

1. Create a new project at [Supabase](https://supabase.com/)
2. Get your project values from Settings → API
3. Link your project:
   ```bash
   supabase login
   supabase link --project-ref <project-id>
   supabase db push
   ```

#### Setup Frontend with Vercel

1. Go to [Vercel](https://vercel.com/) and create a new project
2. Import your GitHub repository
3. Set Framework Preset to "Next.js"
4. Add environment variables:
   - `NEXT_PUBLIC_SUPABASE_URL`
   - `NEXT_PUBLIC_SUPABASE_ANON_KEY`
   - `SUPABASE_SERVICE_ROLE_KEY`
   - `OPENAI_API_KEY` (optional)
5. Click "Deploy"

</details>

---

## 🔄 Updating

To update your local instance:

```bash
npm run update
```

For hosted instances, also run:

```bash
npm run db-push
```

---

## 🐛 Troubleshooting

### Common Issues

**Issue**: Supabase won't start
- **Solution**: Make sure Docker is running

**Issue**: Environment variables not working
- **Solution**: Check `.env.local` file exists and has correct values

**Issue**: Build errors
- **Solution**: Make sure you're using Node.js 18+

---

## 📊 Roadmap

- [ ] Enhanced mobile experience
- [ ] Additional AI provider integrations
- [ ] Advanced analytics dashboard
- [ ] Plugin system
- [ ] API documentation
- [ ] Multi-tenant support

---

<div align="center">

**⭐ Don't forget to star this repository if you find it useful! ⭐**

</div>
