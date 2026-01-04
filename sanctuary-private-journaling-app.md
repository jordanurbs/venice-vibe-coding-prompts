Create a Product Requirements Document (PRD) for a beginner-friendly mood journal app called "Sanctuary" — a private, local-first mood tracking application.

## Core Concept
A personal mood journal where ALL data stays on the user's device. No accounts, no cloud sync, no tracking. The privacy angle is the primary differentiator — "Your feelings are yours alone."

The intelligence powering the AI-generated insights will run through an open source model through the Venice API (private).

## Target User
Someone who wants to track their emotional wellbeing but doesn't trust apps that harvest their most intimate data.

## Must-Have Features (MVP)
1. Log a mood entry: emoji/mood selector + optional text note + timestamp
2. View past entries in a simple list/timeline
3. Local storage only (localStorage or IndexedDB)
4. Clean, calming UI

## Nice-to-Have Features (if time permits)
1. Simple mood trends visualization (last 7 days)
2. Daily prompt/question to encourage reflection
3. Export data as JSON (user owns their data)

## Technical Constraints
- Single-page web app (HTML/CSS/JS or simple React)
- No backend, no authentication
- Mobile-responsive
- Can be run locally or deployed to static hosting

## Design Direction
- Calming, minimal aesthetic
- Soft colors (think: lavender, sage, warm neutrals)
- Gentle animations
- Typography-focused, not cluttered

## Intelligence
- AI-generated insights from a private model on the Venice API (.e.g. llama-3.3-70b)

## Success Criteria
A viewer watching the tutorial can follow along and have a working mood journal by the end that they'd actually want to use.

Generate a complete PRD with: overview, user personas, user stories, functional requirements, non-functional requirements, UI/UX specifications, data model, and technical architecture.
