# Equigrow — Pathways to progress

A student growth planner: timetable-aware learning sessions, department-specific learning paths with resources,
AI tools and projects, languages, a study-abroad (PG) roadmap, curated events and bulletins.

Live: https://prathika591.github.io/EquiGrow/

## Files
| File | Purpose |
|---|---|
| index.html | The whole app (UI + logic) |
| sw.js | Service worker: reminders and "install app" |
| manifest.webmanifest | App name, colours and icons for installing |
| icon-192.png, icon-512.png | App icons |
| firestore.rules | Firestore security rules (paste into Firebase) |

## Tech
HTML/CSS/JavaScript · Firebase Authentication (email + Google) · Cloud Firestore · Firebase AI Logic (Gemini) · GitHub Pages

## Firebase setup
1. Authentication → Sign-in method: enable Email/Password and Google.
2. Authentication → Settings → Authorized domains: add `prathika591.github.io`.
3. Firestore (database id `default`) → Security (Rules): paste `firestore.rules` → Publish.
4. AI services → AI Logic → Get started → Gemini Developer API.
5. The admin email is set in `index.html` (`ADMIN_EMAILS`) and in `firestore.rules`.
