AI-Powered Interview Simulator

A web-based AI interview training platform designed to help users prepare for real-world interviews through behavioral interviews, technical coding challenges, resume analysis, and performance tracking.

Overview

The AI Interview Simulator provides an immersive interview-preparation experience with role-specific mock interviews, AI-generated coding challenges and quizzes, ATS-style resume analysis, and performance insights.

The platform is powered by Google Gemini and uses a full-stack architecture where AI operations are handled securely through the backend.

Key Features

🎤 Mock Interviews

Role-specific interview simulations

Timed technical and behavioral interview sessions

AI-generated interview questions

Real-time AI feedback

Interview evaluation and performance analysis

💻 Coding & Quizzes

AI-generated DSA coding challenges

Multiple-choice questions

Code review and evaluation

Instant feedback

Technical interview practice

📄 ATS Resume Scanner

Upload or paste a resume

Resume compatibility analysis

ATS-style scoring

Suggestions for improving resume content

Identification of missing or weak areas

📊 Performance Dashboard

Review previous interview sessions

Track interview performance

Analyze speaking pace and filler words

Review coding reports

Monitor improvement over time

Technology Stack

Frontend

React

TypeScript

Vite

Tailwind CSS

WebRTC

Web Speech API

Backend

Node.js

Express.js

JWT-secured APIs

Server-side AI processing

Database & Authentication

Supabase

Supabase Authentication

Supabase Database

Supabase Admin

AI

Google Gemini

Gemini 2.5 Flash

Gemini SDK

AI-powered interview generation and evaluation

AI-assisted resume analysis

AI-assisted code evaluation

Architecture

User
  ↓
React + TypeScript Frontend
  ↓
Secure Backend APIs
  ↓
Node.js + Express
  ↓
Google Gemini
  ↓
AI Interview / Resume / Code Analysis
  ↓
Supabase
  ↓
Reports & Session Data

Privacy-Oriented Design

The frontend communicates with the backend rather than directly exposing sensitive AI operations.

User
  ↓
Frontend
  ↓
Backend API
  ├── Authentication
  ├── Interview Processing
  ├── Resume Analysis
  ├── Code Evaluation
  └── Gemini Integration
       ↓
     Gemini

Core User Flow

User signs up and completes profile setup.

User selects an interview role or preparation area.

The platform starts a role-specific AI interview or coding session.

Gemini generates questions and evaluates responses.

Resume analysis can be performed through the ATS scanner.

Session results are stored securely.

The performance dashboard presents previous reports and improvement areas.

AI Capabilities

The platform uses Gemini to support:

Interview question generation

Behavioral interview simulations

Technical interview simulations

Coding challenge generation

Code evaluation

Resume analysis

Interview feedback

Performance analysis

Why This Project

Traditional interview preparation often requires separate tools for mock interviews, coding practice, resume checking, and performance tracking.

This project combines these workflows into a single AI-powered platform so users can practice, receive feedback, analyze their resume, and track their progress in one place.
