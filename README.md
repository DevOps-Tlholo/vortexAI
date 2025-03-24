# VortexAI

A modern web application built with Next.js and AI integration.

## Overview

VortexAI is a Next.js application that integrates AI capabilities using various SDKs and services. The application is built with a focus on modern web development practices, including TypeScript, TailwindCSS, and Firebase integration.

## Features

- AI-powered functionality using @ai-sdk/google and @vapi-ai/web
- Firebase authentication and backend services
- Modern UI components with Radix UI and TailwindCSS
- Theme support with next-themes
- Form handling with React Hook Form
- Date management with dayjs

## Tech Stack

- **Framework**: Next.js 15.2.2
- **Language**: TypeScript
- **Styling**: TailwindCSS
- **Authentication**: Firebase
- **Form Management**: React Hook Form
- **UI Components**: Radix UI
- **AI Integration**: @ai-sdk/google, @vapi-ai/web

## Project Structure

```
vortexAI/
├── app/                 # Next.js app directory
│   ├── (auth)/         # Authentication routes
│   ├── (root)/         # Main application routes
│   └── api/            # API routes
├── components/         # Reusable React components
├── constants/          # Application constants
├── firebase/           # Firebase configuration
├── lib/                # Utility functions and helpers
└── types/              # TypeScript type definitions
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env.local` file
   - Add your Firebase configuration
   - Add any AI service API keys
4. Run the development server:
   ```bash
   npm run dev
   ```

## Development

- Run the development server: `npm run dev`
- Build for production: `npm run build`
- Start the production server: `npm run start`
- Run ESLint: `npm run lint`

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
This project is licensed to Maphume Tlhologelo Ntlatleng
