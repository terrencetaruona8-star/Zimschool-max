# ZimSchool Max — prototype build

This is a mobile-first front-end prototype for the ZimSchool Max learning platform.

## Included
- Dashboard and subject learning paths
- Practice-paper generator with sample questions and automatic marking
- AI tutor demo with sample answers (not connected to a live AI service)
- Interactive food-test lab simulation and lab notebook
- Teacher/school workspace mockups
- Adult learning mini-lessons
- Local progress counters

## Run locally
Open `index.html` in a modern browser. Most features work without a server. The lab notebook uses browser local storage.

## Important limitations
- The questions and lesson content are starter examples, not a complete ZIMSEC syllabus or official past papers.
- The exam feature creates practice questions; it cannot know or guarantee future exam questions.
- The tutor is a demo. A real AI tutor needs a secure server-side AI integration; never put secret API keys in public GitHub Pages code.
- The lab is a simplified visual simulation, not a validated 3D laboratory and not a replacement for supervised practical work.
- Teacher accounts, student privacy controls, cloud sync, payments, real school management, offline install/PWA service worker, and a full 3D lab are not implemented in this prototype.

## Deploy to GitHub Pages
Upload the contents of this folder to the root of your repository, then enable GitHub Pages for the desired branch/root folder. This prototype is static and does not require a build step.

## Recommended next build
1. Confirm subject syllabus coverage and add reviewed content.
2. Add secure backend authentication and AI API proxy.
3. Add a proper question bank, moderation, reporting and data protection.
4. Build a WebGL/Three.js lab with experiment-specific scientific validation and teacher supervision.
