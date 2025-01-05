# MindCraft

A modern, full-stack interactive code editor and snippet sharing platform.

## Overview

MindCraft combines a powerful code editor with community features, allowing developers to write, execute, and share code across multiple programming languages. Built with modern technologies and best practices, it provides a seamless development experience.

## Features

### Interactive Code Editor

- Real-time code editing with syntax highlighting
- Multi-language support (JavaScript, TypeScript, Python, Java, etc.)
- Live code execution with detailed output display
- Customizable editor themes and settings
- Automatic code persistence

### Snippet Sharing

- Create and share code snippets with the community
- Browse shared snippets with advanced filtering
- Star and save favorite snippets
- Comment system with markdown support
- Multiple view options (grid/list)

### User Features

- Secure authentication
- Pro subscription with advanced features
- Language-specific permissions
- User profiles and activity tracking

## Tech Stack

### Frontend

- Next.js 14
- TypeScript
- TailwindCSS
- Framer Motion
- Monaco Editor
- Zustand

### Backend

- Convex (Backend-as-a-Service)
- Clerk Authentication
- Piston API (Code Execution)

## Getting Started

### Prerequisites

- Node.js 18 or higher
- npm or yarn
- Git

### Installation

1. Clone the repository

- git clone https://github.com/yourusername/code-craft.git
- cd code-craft

2. Install dependencies

- npm install
- # or
- yarn install

- cp .env.example .env.local

- NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
- CLERK_SECRET_KEY=your_clerk_secret
- NEXT_PUBLIC_CONVEX_URL=your_convex_url

- npm run dev
- # or
- yarn dev
