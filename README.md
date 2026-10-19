# ApexFit AI — v0.1 starter

**Tagline:** Train Smarter. Get Stronger.

A mobile-first, dark futuristic fitness tracker prototype for beginner bodyweight workouts. Designed to start as a personal app and evolve into a multi-user AI personal trainer.

## Included
- Responsive mobile/desktop dashboard
- Workout plans A (upper body), B (lower body), C (full body)
- Editable exercise targets and local session history
- Rest timer with 30/60/90 second presets
- JSON export of local workout history
- PWA manifest and service worker

## Run locally
Open `index.html` in a browser. For service-worker/PWA testing, serve the folder over localhost or a static hosting provider.

## Current limitations
- Workout history is saved in this browser/device using localStorage.
- No Supabase connection, user authentication, cloud sync, or live AI API is configured yet.
- Coach Corner currently displays basic static guidance. Do not add secret API keys to frontend code.

## Next planned milestones
1. Review the UI and workout flow on mobile.
2. Set up a separate Supabase project for ApexFit AI.
3. Add authentication and user-scoped workout storage with Row Level Security.
4. Add a secure server-side AI coach endpoint and progress-aware coaching.
5. Test offline behavior, data export, and multi-device sync before release.

## Safety note
This is a starter prototype, not medical advice. Stop exercise if you experience sharp pain, chest pain, dizziness, or unusual shortness of breath. Adjust movements to your current ability.
