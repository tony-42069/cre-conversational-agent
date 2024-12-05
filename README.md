# 🤖 CRE Conversational Agent

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-3.3-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![ElevenLabs](https://img.shields.io/badge/ElevenLabs-API-green?style=for-the-badge)](https://elevenlabs.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> 🎯 A powerful, modern web application that transforms text into natural speech using ElevenLabs' cutting-edge AI technology. Built with Next.js and TypeScript for optimal performance and type safety.

![CRE Conversational Agent Preview](/public/preview.png)

## ✨ Features

🎤 **Advanced Voice Synthesis**
- Real-time text-to-speech conversion using ElevenLabs API
- High-quality, natural-sounding voice output
- Customizable voice parameters

💬 **Interactive Chat Interface**
- Clean, modern UI design
- Real-time message updates
- Message history with timestamps
- Responsive layout for all devices

🎮 **Audio Controls**
- Play/Pause functionality
- Progress tracking
- Volume control
- Playback speed adjustment

🛠️ **Technical Features**
- Built with Next.js 14 and App Router
- Type-safe with TypeScript
- Styled using Tailwind CSS
- Component library built on Radix UI
- Responsive design

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have:
- Node.js 18.x or later
- npm or yarn
- ElevenLabs API key ([Get one here](https://elevenlabs.io/))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/tony-42069/cre-conversational-agent.git
   cd cre-conversational-agent
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Then edit `.env` with your ElevenLabs API key:
   ```env
   ELEVENLABS_API_KEY=your_api_key_here
   NEXT_PUBLIC_APP_URL=http://localhost:3000
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser 🎉

## 📁 Project Structure

```
src/
├── app/                  # Next.js App Router
│   ├── api/             # API routes
│   │   └── speech/      # Text-to-speech endpoint
│   ├── layout.tsx       # Root layout
│   └── page.tsx         # Home page
├── components/          # React components
│   ├── ChatInterface/   # Main chat component
│   ├── MessageInput/    # Text input component
│   └── AudioPlayer/     # Custom audio player
└── lib/                 # Utilities
    ├── elevenlabs.ts    # ElevenLabs API integration
    └── utils.ts         # Helper functions
```

## 🛠️ Technology Stack

- **Frontend Framework**: Next.js 14
- **UI Library**: React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Voice Synthesis**: ElevenLabs API
- **Components**: Radix UI
- **State Management**: React Hooks
- **HTTP Client**: Native fetch API

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Tony**
- GitHub: [@tony-42069](https://github.com/tony-42069)

## 🙏 Acknowledgments

- [ElevenLabs](https://elevenlabs.io/) for their amazing text-to-speech API
- [Vercel](https://vercel.com) for hosting and deployment
- [Radix UI](https://www.radix-ui.com/) for accessible component primitives

---

<div align="center">

Built with Next.js and ElevenLabs

</div>