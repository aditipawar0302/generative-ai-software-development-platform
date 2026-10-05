# Generative AI Software Development Platform

An AI-powered software development platform that allows users to describe an application in natural language and generate a functional web application with a live preview.

## Overview

The Generative AI Software Development Platform is a full-stack application designed to simplify web application development using Generative AI.

Users can enter a natural-language prompt describing the application they want to build. The platform uses Gemini AI to generate application code, display the generated code, and render the application through a live preview.

The platform also provides project management, authentication, persistent workspaces, and AI-assisted application improvement.

## Features

- AI-powered application generation from natural-language prompts
- Live application preview
- Generated source code viewer
- AI-assisted application improvement
- User authentication
- Persistent projects and workspaces
- Chat-based interaction with the AI
- Credit-based generation system
- Responsive and modern user interface
- Project management and deletion
- Error handling and AI-assisted fixing
- Application export functionality

## Tech Stack

### Frontend
- Next.js
- React.js
- TypeScript
- Tailwind CSS
- Shadcn UI

### Backend
- Next.js App Router
- API Routes
- Prisma ORM
- PostgreSQL

### Database & Storage
- Supabase
- PostgreSQL
- Supabase Storage

### Authentication
- Clerk

### Generative AI
- Google Gemini AI

### AI Application Preview
- Sandpack

### Security & Infrastructure
- Arcjet
- Environment-based configuration

## Project Architecture

```text
Generative AI Software Development Platform
│
├── app/
│   ├── api/
│   │   ├── gen-ai-code/
│   │   └── improve/
│   ├── (auth)/
│   └── (main)/
│
├── components/
│   ├── ChatPanel
│   ├── CodePanel
│   ├── WorkspaceClient
│   └── UI Components
│
├── actions/
│   ├── projects.ts
│   └── workspace.ts
│
├── lib/
│   ├── prisma.ts
│   ├── checkUser.ts
│   ├── arcjet.ts
│   └── utils.ts
│
├── prisma/
│   ├── schema.prisma
│   └── migrations/
│
├── public/
├── types/
└── package.json