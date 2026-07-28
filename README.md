<div align="center">

# EduVaani

### Understand English. Learn in Your Own Language.

An AI-powered multilingual educational assistant built with **Google Gemma 4** that helps learners understand educational content through simple, concept-based explanations instead of literal translations.

Built for **Build with Gemma 4 | AI Durg Hackathon**  
**Track:** Vaani – Voice First Translation for Bharat

<br>

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=nextdotjs)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Gemma 4](https://img.shields.io/badge/Gemma-4-4285F4?style=for-the-badge)]()
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)
[![Vercel](https://img.shields.io/badge/Vercel-Deployed-black?style=for-the-badge&logo=vercel)](https://vercel.com/)

</div>

---

## Live Demo

**Application:** https://your-demo-link.vercel.app

---

# The Problem

Educational resources are increasingly available online, but much of the content is written in English. For many adult and elderly learners in India, understanding these resources becomes challenging—not because of the concepts themselves, but because of the language barrier.

Traditional translation tools often translate sentences literally, making complex topics even harder to understand.

EduVaani approaches this differently.

Instead of translating words, it explains ideas like a teacher—using simple language, preserving important technical terms, and making learning easier in the learner's preferred language.

---

# Features

| Feature | Description |
|----------|-------------|
| AI Explanations | Generate easy-to-understand educational explanations using Gemma 4 |
| Voice Mode | Speak naturally and receive spoken explanations |
| Speech Recognition | Convert spoken English into text before AI processing |
| PDF Support | Upload PDFs and generate concept-based explanations |
| Learning History | View previously generated explanations anytime |
| Secure Login | Google & Email authentication powered by Supabase |
| Settings | Personalize your learning experience |

---

# Tech Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | Next.js 15, React, TypeScript |
| Styling | Tailwind CSS, shadcn/ui, Framer Motion |
| Backend | Next.js API Routes |
| AI | Google AI Studio API, Gemma 4 |
| Database | Supabase |
| Authentication | Supabase Auth |
| Deployment | Vercel |

---

# Project Architecture

<p align="center">

Replace this section with your architecture diagram.

</p>

```
          User
            │
            ▼
     Next.js Frontend
            │
            ▼
        API Routes
            │
            ▼
      Prompt Builder
            │
            ▼
 Google AI Studio API
        Gemma 4
            │
            ▼
    AI Generated Response
            │
            ▼
         Supabase
            │
            ▼
        User Interface
```

---

# Application Pages

### Landing Page

Introduces EduVaani, its purpose, and the learning experience.

---

### Login

Secure authentication using Google or Email through Supabase.

---

### Dashboard

Provides quick access to learning features and recently generated explanations.

---

### Explanation Page

Paste educational content or upload a PDF to receive AI-generated explanations in the selected language.

---

### History

Displays previously generated explanations for future reference.

---

### Settings

Manage preferences and personalize the application experience.

---

# Screenshots

Replace the placeholders below with screenshots from your application.

| Landing Page | Dashboard |
|--------------|-----------|
| ![](screenshots/landing.png) | ![](screenshots/dashboard.png) |

| Explanation Page | Voice Mode |
|------------------|------------|
| ![](screenshots/explain.png) | ![](screenshots/voice.png) |

| History | Settings |
|----------|----------|
| ![](screenshots/history.png) | ![](screenshots/settings.png) |

---

# How EduVaani Uses Gemma 4

EduVaani uses **Google's Gemma 4** through the **Google AI Studio API** to generate learner-friendly educational explanations.

Instead of asking the model to translate text, we guide it using carefully structured prompts that encourage it to:

- Explain concepts in simple language
- Preserve important technical terms
- Break complex topics into smaller ideas
- Generate conversational responses suitable for learners

This teaching-first approach enables EduVaani to deliver explanations that are easier to understand than direct translations.

---

# Getting Started

Clone the repository.

```bash
git clone https://github.com/your-username/EduVaani.git
```

Navigate into the project.

```bash
cd EduVaani
```

Install dependencies.

```bash
npm install
```

Run the development server.

```bash
npm run dev
```

The application will be available at:

```
http://localhost:3000
```

---

# Environment Variables

Create a `.env.local` file.

```env
GOOGLE_API_KEY=

SUPABASE_URL=

SUPABASE_ANON_KEY=
```

---

# Team

### NeuroStars

Built with the vision of making educational content more understandable and accessible through multilingual AI-powered learning.

---

# Hackathon

**Build with Gemma 4 | AI Durg Hackathon**

**Track:** Vaani – Voice First Translation for Bharat

---

# License

This project is licensed under the **MIT License**.

---

<div align="center">

### Learning should never be limited by language.

**EduVaani** combines the power of **Gemma 4**, voice interaction, and multilingual AI to make educational content easier to understand for learners across India.

</div>
