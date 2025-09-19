# Traino – AI‑Powered Training Management

An enterprise‑grade training management platform that uses AI to create, manage and deliver interactive training. Built with **Next.js 15**, **React 19**, **TypeScript**, **Tailwind CSS**, **Prisma ORM** and **MySQL** in a multi‑tenant architecture.

Live: [app.traino.ai](https://app.traino.ai)

## Overview

Traino enables companies to create AI‑driven training content from videos and documents. It provides multi‑role dashboards (Super Admin, Admin, User) with granular access control, intuitive UI built with Radix UI and shadcn/ui, dark/light mode and responsive design.

## Features

- **Training management:** Embed YouTube videos or upload files, process transcripts, and generate AI summaries, key points and quizzes using Google Generative AI.
- **Multi‑tenant & RBAC:** Support for companies, departments and role‑based access (Super Admin, Admin, User) with secure sessions and RLS.
- **User management:** Assign trainings with due dates and reminders; track progress and performance analytics.
- **Content processing:** YouTube API for metadata and transcripts, AWS S3 for storage, AI‑based content analysis.
- **Authentication:** Better Auth with sessions, OAuth and email verification.
- **Communication:** Automated notifications, reminders and welcome emails using Resend and Nodemailer.
- **Dashboards:** Real‑time completion tracking, performance analytics and role‑based dashboards.
- **Mobile‑optimised:** Responsive design with touch support.

## Tech Stack

- **Framework:** Next.js 15, React 19, TypeScript
- **Styling:** Tailwind CSS, Radix UI, shadcn/ui
- **Database & ORM:** MySQL with Prisma ORM
- **Storage:** AWS S3
- **AI:** Google Generative AI for summarisation and quiz generation
- **Email:** Resend & Nodemailer
