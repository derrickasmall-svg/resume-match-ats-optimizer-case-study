# Architecture Overview

## Application Type

Resume Match is a front-end React and TypeScript application built with Vite.

## Main Functional Areas

- Landing page
- Resume scanner
- Resume builder
- Cover letter generator
- Job tracker
- Results dashboard
- AI service layer

## High-Level Flow

1. User enters or uploads resume content.
2. User provides a job description.
3. Application compares resume content against job requirements.
4. AI service generates improvement suggestions.
5. User reviews results and updates resume content.
6. Job tracker stores application progress.

## Component-Based Design

The application uses reusable components for each major workflow. This makes the app easier to maintain, expand, and troubleshoot.

## API Design

AI-related functionality is separated into a service layer. This prevents UI components from directly managing API request logic.

## Security Design

Sensitive values such as API keys are stored in environment variables and excluded from public repositories.