@"
# CRE Conversational Agent

A Next.js-based web application that integrates with ElevenLabs' text-to-speech API to create an interactive conversational agent.

## Features

- Real-time text-to-speech conversion using ElevenLabs API
- Modern chat interface with message history
- Audio playback controls
- Responsive design using Tailwind CSS
- Built with Next.js and TypeScript

## Prerequisites

- Node.js 18.x or later
- npm or yarn
- ElevenLabs API key

## Getting Started

1. Clone the repository:
\`\`\`bash
git clone https://github.com/tony-42069/cre-conversational-agent.git
cd cre-conversational-agent
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Create a \`.env\` file in the root directory and add your ElevenLabs API key:
\`\`\`env
ELEVENLABS_API_KEY=your_api_key_here
NEXT_PUBLIC_APP_URL=http://localhost:3000
\`\`\`

4. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

\`\`\`
src/
├── app/
│   ├── api/
│   │   └── speech/
│   │       └── route.ts
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── ChatInterface.tsx
│   ├── MessageInput.tsx
│   └── AudioPlayer.tsx
└── lib/
    ├── elevenlabs.ts
    └── utils.ts
\`\`\`

## Technology Stack

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- ElevenLabs API
- Radix UI Components

## License

MIT

## Author

Tony
"@ | Out-File -FilePath README.md -Encoding utf8